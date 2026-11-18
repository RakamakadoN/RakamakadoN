<!--
  Samurai Cinema • GitHub Profile
  Design: image-first, content-second, no JavaScript.
  Previous graphics remain in the repository; the new image is an additional asset.
-->
<p align="center">
  <img src="./assets/samurai-cinema.webp" width="100%" alt="Cinematic Japanese-inspired banner: empty ornate samurai armor, katana on a stand, red sun, and Diyaz Seisenbayev." />
</p>

<p align="center">
  <sub>探究 · 守護 · 創造 &nbsp; | &nbsp; INQUIRY · PROTECTION · CREATION</sub>
</p>

# Diyaz Seisenbayev 👋

AI developer building practical tools for debugging, automation, and business systems.

I focus on **silent failures**: situations where software reports success while a file, record, workflow, or result is wrong or missing. My work connects debugging, AI-assisted investigation, and practical business systems — with an emphasis on **reproducible evidence rather than confident guesses**.

[![XERJ Corpus Hub Contributor](https://hub.xerj.org/contributors/RakamakadoN/badge.svg)](https://hub.xerj.org/contributors/RakamakadoN)
[![OpenAI merged contributor](https://img.shields.io/badge/OpenAI-merged%20contributor-238636?logo=github&logoColor=white)](https://github.com/openai/codex-security/pull/2163)

---

## XERJ Corpus Hub · Selected open-source work

**Ghost Busters Skill was selected for the [XERJ Corpus Hub](https://hub.xerj.org/contributors/RakamakadoN)** on **October 24, 2026**.

XERJ included a **pinned, indexed snapshot of my open-source repository** in its reference corpus library for AI coding agents. Agents can search the real source code and retrieve worked examples with references to the original repository, commit, file, and line — rather than relying on a general description.

- **What was included:** [`RakamakadoN/ghost-busters-skill`](https://hub.xerj.org/corpus/rakamakadon--ghost-busters-skill) — a snapshot of **23 source files (135.8 KB)** at pinned commit [`b583898c8c`](https://github.com/RakamakadoN/ghost-busters-skill/commit/b583898c8c3e4e1f07fa2cdf257093350baf3e71).
- **Selected contribution:** XERJ highlights one commit involving the debugging scanners and reference tests (**3 files / 179 lines** attributed in its contributor registry).
- **Attribution and licence:** Listed publicly under **Diyaz Seisenbayev (@RakamakadoN)**. The corpus page records author permission and **MIT licensing with credit**.
- **What this proves:** Independent selection and indexing of the project as an AI-agent reference corpus. **It does not claim a merge into XERJ's core engine, employment, or endorsement of other projects.**

**Verify:** [Contributor profile](https://hub.xerj.org/contributors/RakamakadoN) · [Live corpus](https://hub.xerj.org/corpus/rakamakadon--ghost-busters-skill) · [Selected GitHub commit](https://github.com/RakamakadoN/ghost-busters-skill/commit/b583898c8c3e4e1f07fa2cdf257093350baf3e71)

---

## OpenAI open-source milestone

[**PR #2163**](https://github.com/openai/codex-security/pull/2163) was **merged into `openai/codex-security:main`** on November 4, 2026 (UTC).

**Why this mattered:** Scan activity could attribute a command to the **wrong file** when a repository path contained a POSIX shell-escaped space or tab. For example, reading `src/my\ file.ts` could be recorded as `src/my`. That's misleading evidence during investigation.

**What changed:** The fix preserves escaped whitespace in the relevant shell contexts, handles recorded arguments as literal operands, and avoids misidentifying unrelated quoted text as filenames.

**How it was verified:** The PR documents a reproduction on the original main branch, activity-adapter scenarios and SDK tests, plus checks for types, formatting, and portable plugins. [Read the actual change and discussion](https://github.com/openai/codex-security/pull/2163).

> “Cool! Thank you for the contribution!”  
> — [@mldangelo-oai, PR reviewer](https://github.com/openai/codex-security/pull/2163#issuecomment-6640638679)

<details>
<summary><strong>⚔️ Contribution focus — what changed</strong></summary>

An open-source fix addressing **shell-escaped whitespace handling in repository paths**. The linked pull request is the source of truth for the change, discussion, and merge status.

</details>

---

## Featured projects

A *ghost* is a defect that does not produce an obvious failure: a success message with missing rows, an apparently green check with incomplete behavior, or a plausible result backed by stale data.

### Ghost Busters Skill · Investigating silent failures

[**Ghost Busters Skill**](https://github.com/RakamakadoN/ghost-busters-skill) — read-only debugging protocol and static analyzers for silent failures. Selected work is included in the XERJ Corpus Hub.

- **Problem addressed:** Error logs and conventional pass/fail checks can miss logically incorrect outcomes.
- **What is provided:** An **8-phase investigation protocol**, a catalogue of **13 silent-bug classes**, read-only scanners, offline evidence gates, and synthetic regression examples.
- **Inspect the work:** [Repository](https://github.com/RakamakadoN/ghost-busters-skill) · [Bug taxonomy](https://github.com/RakamakadoN/ghost-busters-skill/blob/main/references/ghost-classes.md) · [Tests](https://github.com/RakamakadoN/ghost-busters-skill/tree/main/tests)

### Ghost Busters PRO · Code-analysis tooling

[**Ghost Busters PRO**](https://github.com/RakamakadoN/ghost-busters-pro) — security and code-analysis tooling. *(Repository access may be restricted.)*

The project is linked for reference; access and independently inspectable public evidence may be limited.

### Open-source contribution · OpenAI

[**OpenAI codex-security contribution**](https://github.com/openai/codex-security/pull/2163) — fixed shell-escaped whitespace handling in repository paths; **PR #2163 merged into `main`**.

The pull request above is a public case study with the original problem statement, changes, tests, review, and merge history.

---

## Areas of interest

AI agents · Developer tooling · CRM/ERP · Static analysis · Geospatial systems

### Engineering loop

**01 Observe** · Form a testable hypothesis  
**02 Reproduce** · Bound the scenario  
**03 Verify** · Collect inspectable evidence  
**04 Improve** · Patch and protect with tests

> Build things that work. Investigate things that fail silently. Let evidence distinguish a hypothesis from a finding.

My working rule: **a hypothesis is not a finding, a passing command is not proof of correct behavior, and a fix needs a reproducible check.**

---

<p align="center">
  <i><strong>“Mastery of the sword, untested in battle,<br />
  is like learning to swim on dry land.”</strong></i>
</p>
<p align="center">
  <sub>— Hanshirō Tsugumo · <i>Harakiri</i> (1962) · English rendering</sub>
</p>

<details>
<summary><strong>Katana glint · animation</strong></summary>
<p align="center">
  <img src="./assets/katana-glint.gif" width="700" alt="Animated katana blade with a traveling gold-white glint" />
</p>
</details>

---

<p align="center">
  <sub>侍の美学 · Japanese-inspired visual design · Code, evidence &amp; craft</sub>
</p>

> Badges link to verifiable contributions: the XERJ badge recognizes selected **Ghost Busters Skill** work, and the OpenAI badge links to a merged open-source PR. Neither badge implies employment, organization membership, endorsement, or certification.
