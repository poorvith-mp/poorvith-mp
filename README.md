<div align="center">

<!-- Top Banner: Foresight Wide -->
<a href="https://poorvithmp.com">
  <img src="./assets/foresight-banner-wide.png" width="100%" alt="Poorvith M P — I Foresight before small problems become expensive." />
</a>

<br/><br/>

<!-- Logo & Core Profile Identity -->
<a href="https://poorvithmp.com">
  <img src="./assets/logo-mark.svg" width="68" height="68" alt="PM Aperture Mark" />
</a>

# POORVITH M P

### <i>I Foresight before small problems become expensive.</i>

<p align="center">
  <strong>Open Source Builder / Student Builder • Local-First Privacy & AI Agent Systems</strong>
  <br/>
  <span>Student Developer • Indie Builder</span>
</p>

<!-- Live Animated System Indicator -->
<img src="./assets/live-status.svg" width="100%" alt="Foresight Engine Live Status" />

<br/><br/>

<!-- Identity Action Badges -->
<p align="center">
  <a href="https://poorvithmp.com"><img src="https://img.shields.io/badge/Portfolio-poorvithmp.com-cda03a?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=08090b" alt="Portfolio"/></a>
  <a href="mailto:contact@poorvithmp.com"><img src="https://img.shields.io/badge/Direct_Desk-contact@poorvithmp.com-131417?style=for-the-badge&logo=gmail&logoColor=cda03a&labelColor=08090b" alt="Email"/></a>
  <a href="https://linkedin.com/in/poorvithmp"><img src="https://img.shields.io/badge/LinkedIn-poorvithmp-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=08090b" alt="LinkedIn"/></a>
  <a href="https://x.com/poorvith_mp"><img src="https://img.shields.io/badge/X-@poorvith__mp-131417?style=for-the-badge&logo=x&logoColor=white&labelColor=08090b" alt="X"/></a>
  <a href="https://github.com/poorvith-mp?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-cda03a?style=for-the-badge&logo=github&logoColor=08090b&labelColor=08090b" alt="GitHub Repos"/></a>
</p>

</div>

---

## 🏛️ About Me & The Foresight Principle

I'm a B.Tech Computer Science and Engineering student at Presidency University and an open-source builder. I look for the friction developers learn to tolerate, turn it into a focused tool, and keep every decision visible from the first check to the working code.

Most software failures don't start as big outages. They start when an API key gets pasted into an LLM prompt, a local `.env` drifts from what the repo expects, a stack trace gets filed without git or runtime context, or an agent runs with vague instructions.

That's what **Foresight** means in my work: catch the failure mode on your own machine before it leaves your browser, breaks a build, or turns into an expensive cleanup.

<br/>

<table>
<tr>
<td width="25%" align="center">
  <strong>🛡️ Foresight First</strong><br/>
  <sub>Catch leaks, runtime mismatches, and broken state before they leave your machine</sub>
</td>
<td width="25%" align="center">
  <strong>🔒 Zero-Exposure Privacy</strong><br/>
  <sub>100% browser-local Web Crypto workspaces and offline-first CLIs</sub>
</td>
<td width="25%" align="center">
  <strong>⚡ Useful Before Impressive</strong><br/>
  <sub>Fast local execution, zero-signup web apps, and direct npx commands</sub>
</td>
<td width="25%" align="center">
  <strong>🔍 Honest Boundaries</strong><br/>
  <sub>Open source repositories, clear permission scopes, and documented limits</sub>
</td>
</tr>
</table>

---

## 🚀 My Tools

<table width="100%">
<tr>
<td width="50%" valign="top">

<!-- AIScrubber Card (Row 1, Left) -->
<a href="https://aiscrubber.poorvithmp.com">
  <img src="./assets/aiscrubber-cover.svg" width="100%" alt="AIScrubber Cover"/>
</a>

### <img src="./assets/aiscrubber-logo.svg" width="22" height="22" valign="middle" alt="AIScrubber Logo"/> [AIScrubber](https://github.com/poorvith-mp/aiscrubber)
> **Browser-local AI privacy scrubber (`3.0.0`), CLI, and MCP server (`@poorvithmp/aiscrubber 2.4.0` · Release `v2.3.0`).**

- **The Problem:** Developers paste API keys, database URLs, and raw logs into LLM chats or public issues. Once a secret leaves your machine, you can't un-send it.
- **The Solution:** Runs 5 client-side workspaces: deterministic credential scrubber (stable `{{TYPE_N}}` tokens), reversible prompt roundtrip with AES-GCM encrypted `.aiscrub.json` vaults, zero-width Unicode watermark cleaner, image EXIF stripper, and canvas redactor.
- **Tech Stack:** React 19 · TypeScript · Web Crypto API · Tailwind CSS v4 · Vite · MCP Server · Node CLI

<p>
  <a href="https://aiscrubber.poorvithmp.com"><img src="https://img.shields.io/badge/Launch_App-aiscrubber.poorvithmp.com-cda03a?style=flat-square" alt="Launch AIScrubber"/></a>
  <a href="https://www.npmjs.com/package/@poorvithmp/aiscrubber"><img src="https://img.shields.io/badge/npm-@poorvithmp/aiscrubber_2.4.0-cb3837?style=flat-square&logo=npm" alt="AIScrubber npm"/></a>
  <a href="https://github.com/poorvith-mp/aiscrubber"><img src="https://img.shields.io/badge/Release-v2.3.0-131417?style=flat-square&logo=github" alt="AIScrubber GitHub"/></a>
</p>

<details>
<summary><strong>View architectural highlights</strong></summary>

- 100% browser-local Web Crypto execution (`AES-GCM` encrypted session vaults) with zero telemetry
- Invisible LLM watermark stripper (`\u200B`, `\u200C`, `\u200D`, `\uFEFF`, `\u2060`)
- Terminal CLI (`npx @poorvithmp/aiscrubber`) and stdio MCP server (`aiscrubber-mcp`) for Claude Desktop, Cursor, and Codex
- Client-side JPEG/PNG/WebP EXIF metadata stripper and brush/box image redactor

</details>

</td>
<td width="50%" valign="top">

<!-- SafeGen Card (Row 1, Right) -->
<a href="https://safegen.poorvithmp.com">
  <img src="./assets/safegen-cover.svg" width="100%" alt="SafeGen Cover"/>
</a>

### <img src="./assets/safegen-logo.svg" width="22" height="22" valign="middle" alt="SafeGen Logo"/> [SafeGen](https://github.com/poorvith-mp/safegen)
> **Browser-local credential generator (`v2.0.0`) & owner-approved agent action broker (`@poorvithmp/safegen 3.1.1` · `core 2.2.0`).**

- **The Problem:** Online password generators can't be audited while you type, and telling an AI agent "don't leak my token" isn't a real permission boundary.
- **The Solution:** Combines a browser-local `crypto.getRandomValues()` credential generator (rejection sampling across Password, Passphrase, PIN, and Pattern modes) with a local owner-approved action broker CLI and MCP server for fixed GitHub and Cloudflare actions.
- **Tech Stack:** React 19 · TypeScript · Web Crypto API · Node.js CLI & MCP · Tailwind CSS v4 · GSAP

<p>
  <a href="https://safegen.poorvithmp.com"><img src="https://img.shields.io/badge/Launch_App-safegen.poorvithmp.com-cda03a?style=flat-square" alt="Launch SafeGen"/></a>
  <a href="https://www.npmjs.com/package/@poorvithmp/safegen"><img src="https://img.shields.io/badge/npm-@poorvithmp/safegen_3.1.1-cb3837?style=flat-square&logo=npm" alt="SafeGen npm"/></a>
  <a href="https://github.com/poorvith-mp/safegen"><img src="https://img.shields.io/badge/Release-v2.0.0-131417?style=flat-square&logo=github" alt="SafeGen GitHub"/></a>
</p>

<details>
<summary><strong>View architectural highlights</strong></summary>

- Unbiased cryptographic rejection sampling via Web Crypto API with live bit-entropy and offline crack-time scoring
- Owner-approved local broker (`npx @poorvithmp/safegen`) and MCP server (`safegen-mcp`) keeping tokens inside a private OS session
- Shared `@poorvithmp/safegen-core` (`2.2.0`) cryptographic engine
- Local-only copy history with zero network calls or analytics

</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<!-- GradeForge Card (Row 2, Left) -->
<a href="https://gradeforge.poorvithmp.com">
  <img src="./assets/gradeforge-cover.svg" width="100%" alt="GradeForge Cover"/>
</a>

### <img src="./assets/gradeforge-logo.svg" width="22" height="22" valign="middle" alt="GradeForge Logo"/> [GradeForge](https://github.com/poorvith-mp/gradeforge)
> **Offline-first credit-weighted SGPA/CGPA engine & Target What-If planner (Release `v1.0.0` · PWA Workspace `2.1.0`).**

- **The Problem:** University grading scales vary widely, and ad-heavy online calculators break on custom credits, multi-semester weighting, or forward-looking CGPA planning.
- **The Solution:** Preloaded with 8 university and international grading presets (VTU 10-Point, Anna University, Mumbai University, KTU, JNTU, UGC 10-Point, US 4.0, ECTS) plus a custom scale builder and Target CGPA What-If planner.
- **Tech Stack:** React 18 · TypeScript · Vite PWA · Tailwind CSS · LocalStorage Persistence

<p>
  <a href="https://gradeforge.poorvithmp.com"><img src="https://img.shields.io/badge/Launch_App-gradeforge.poorvithmp.com-cda03a?style=flat-square" alt="Launch GradeForge"/></a>
  <a href="https://poorvithmp.com/products/gradeforge"><img src="https://img.shields.io/badge/Product_Page-poorvithmp.com-131417?style=flat-square" alt="GradeForge Product Page"/></a>
  <a href="https://github.com/poorvith-mp/gradeforge"><img src="https://img.shields.io/badge/Release-v1.0.0-131417?style=flat-square&logo=github" alt="GradeForge GitHub"/></a>
</p>

<details>
<summary><strong>View architectural highlights</strong></summary>

- Multi-semester credit-weighted SGPA and cumulative CGPA calculation with complete formula visibility
- Target CGPA What-If planner showing the exact semester average needed across remaining credits
- Offline-first Progressive Web App (`2.1.0`) with JSON backup/restore, CSV export, and print-clean academic summary
- 100% browser-local storage with zero signups or tracking

</details>

</td>
<td width="50%" valign="top">

<!-- EnvPreflight Card (Row 2, Right) -->
<a href="https://envpreflight.poorvithmp.com">
  <img src="./assets/envpreflight-cover.svg" width="100%" alt="EnvPreflight Cover"/>
</a>

### <img src="./assets/envpreflight-logo.svg" width="22" height="22" valign="middle" alt="EnvPreflight Logo"/> [EnvPreflight](https://github.com/poorvith-mp/envpreflight)
> **Local runtime, Docker service, port, and `.env` readiness auditor (`@poorvithmp/envpreflight 1.1.0` · Release `v1.0.0`).**

- **The Problem:** Developers clone a repo and waste an hour debugging an app bug that's actually a Node/Python version mismatch, a missing `.env` key, or a stopped Docker container.
- **The Solution:** Inspects project manifests (`package.json`, `.nvmrc`, `pyproject.toml`, `go.mod`, `Cargo.toml`, `docker-compose.yml`, `.env.example`) and reports exact fixes across CLI, MCP, VS Code, and GitHub Actions.
- **Tech Stack:** TypeScript · Node.js · MCP Server · VS Code Extension · GitHub Action · pnpm Monorepo

<p>
  <a href="https://envpreflight.poorvithmp.com"><img src="https://img.shields.io/badge/Subdomain-envpreflight.poorvithmp.com-cda03a?style=flat-square" alt="EnvPreflight Subdomain"/></a>
  <a href="https://www.npmjs.com/package/@poorvithmp/envpreflight"><img src="https://img.shields.io/badge/npm-@poorvithmp/envpreflight_1.1.0-cb3837?style=flat-square&logo=npm" alt="npm package"/></a>
  <a href="https://www.npmjs.com/package/@poorvithmp/envpreflight-mcp"><img src="https://img.shields.io/badge/MCP-envpreflight--mcp_1.1.0-131417?style=flat-square" alt="MCP package"/></a>
</p>

<details>
<summary><strong>View architectural highlights</strong></summary>

- Multi-runtime validation for Node.js, Python, Go, Rust, Java, and Docker Engine
- TCP service reachability and port collision checks for PostgreSQL (5432), Redis (6379), MySQL (3306), and MongoDB (27017)
- Zero-leakage `.env` key parity auditor (compares key names only; secret values are never read or logged)
- Published CLI (`@poorvithmp/envpreflight`), MCP server (`@poorvithmp/envpreflight-mcp`), VS Code extension, and composite GitHub Action (`poorvith-mp/envpreflight@v1`)

</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<!-- Skillary Card (Row 3, Left) -->
<a href="https://poorvithmp.com/products/skillary">
  <img src="./assets/skillary-cover.svg" width="100%" alt="Skillary Cover"/>
</a>

### <img src="./assets/skillary-logo.svg" width="22" height="22" valign="middle" alt="Skillary Logo"/> [Skillary](https://github.com/poorvith-mp/skillary) & [skillary-agents](https://github.com/poorvith-mp/skillary-agents)
> **Deterministic AI agent skills registry (`v4.1.0`) — 277 skills across 12 category repos + `skillary-agents` (`v4.1.0`) crew protocol.**

- **The Problem:** Loading hundreds of skills into a coding agent bloats the context window, while vague instructions make multi-step tasks drift.
- **The Solution:** `Skillary` (`v4.1.0`) indexes 277 focused agent skills across 12 category repositories with a zero-dependency `skillary.py` CLI, paired with `skillary-agents` (`v4.1.0`) and its `crew.py` CLI for 6-role, 8-playbook multi-agent handoffs.
- **Tech Stack:** Agent Skills Spec · Python 3.12 · SQLite FTS5 · Claude Code · Codex · Cursor · Windsurf · Gemini CLI

<p>
  <a href="https://poorvithmp.com/products/skillary"><img src="https://img.shields.io/badge/Catalogue-poorvithmp.com/products/skillary-cda03a?style=flat-square" alt="Skillary Catalogue"/></a>
  <a href="https://github.com/poorvith-mp/skillary/releases/tag/v4.1.0"><img src="https://img.shields.io/badge/Skillary-v4.1.0-131417?style=flat-square&logo=github" alt="Skillary v4.1.0"/></a>
  <a href="https://github.com/poorvith-mp/skillary-agents/releases/tag/v4.1.0"><img src="https://img.shields.io/badge/skillary--agents-v4.1.0-131417?style=flat-square&logo=github" alt="skillary-agents v4.1.0"/></a>
</p>

<details>
<summary><strong>View architectural highlights</strong></summary>

- 12 Category Repos: Developer (58), Marketing (44), Game Dev (26), Business (23), Design (21), Education (21), Agents (17), Personal (15), Writing (15), Sales (14), Finance (12), Legal (11)
- Zero-dependency `python3 skillary.py` CLI for searching, inspecting, recommending, and installing skills across 6 agent hosts
- `skillary-agents` (`v4.1.0`) orchestration companion with `python3 crew.py`, 6 role templates, and 8 playbooks
- Sub-millisecond SQLite FTS5 index (`dist/skills.db`) and machine-readable `dist/skills.json`

</details>

</td>
<td width="50%" valign="top">

<!-- Crashpack Card (Row 3, Right) -->
<a href="https://crashpack.poorvithmp.com">
  <img src="./assets/crashpack-cover.svg" width="100%" alt="Crashpack Cover"/>
</a>

### <img src="./assets/crashpack-logo.svg" width="22" height="22" valign="middle" alt="Crashpack Logo"/> [Crashpack](https://github.com/poorvith-mp/crashpack)
> **Local-first CLI bug report generator & CI failure bundler (`crashpack 0.4.2` · Release `v0.4.2`).**

- **The Problem:** A raw stack trace leaves out git state, runtime versions, and recent logs, but pasting raw terminal output into a bug report leaks credentials.
- **The Solution:** Collects local diagnostic context, applies pattern + Shannon-entropy secret redaction, deduplicates error hashes, and writes a reviewable Markdown or JSON report locally or via its composite GitHub Action.
- **Tech Stack:** TypeScript · Node.js · GitHub Actions · Commander · Execa · Vitest · tsup

<p>
  <a href="https://crashpack.poorvithmp.com"><img src="https://img.shields.io/badge/Subdomain-crashpack.poorvithmp.com-cda03a?style=flat-square" alt="Crashpack Subdomain"/></a>
  <a href="https://www.npmjs.com/package/crashpack"><img src="https://img.shields.io/badge/npm-crashpack_0.4.2-cb3837?style=flat-square&logo=npm" alt="npm package"/></a>
  <a href="https://github.com/poorvith-mp/crashpack/releases/tag/v0.4.2"><img src="https://img.shields.io/badge/Release-v0.4.2-131417?style=flat-square&logo=github" alt="Crashpack GitHub"/></a>
</p>

<details>
<summary><strong>View architectural highlights</strong></summary>

- Pattern + Shannon-entropy redaction pipeline stripping AWS keys, GitHub/Stripe tokens, JWTs, private keys, and `.env` secrets
- Composite GitHub Action (`poorvith-mp/crashpack@v0.4.2`) for automatic CI failure bundling and artifact upload
- Error-hash deduplication and offline sourcemap stack frame resolution
- Explicit opt-in clipboard (`--copy`) and reviewed GitHub issue creation (`--issue`)

</details>

</td>
</tr>
</table>

---

## 🌐 Open Source Contributions

*Upstream collaborator engineering, security hardening, and cross-platform architecture contributions.*

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🔒 [watermarks-remover](https://github.com/guillaumemeyer/watermarks-remover)
`guillaumemeyer/watermarks-remover` • <img src="https://img.shields.io/badge/Role-Collaborator-cda03a?style=flat-square" alt="Collaborator"/>

- **What it solves:** Strips invisible zero-width Unicode tracking vectors (`\u200B`, `\u200C`, `\u200D`, `\uFEFF`, `\u2060`) and C2PA metadata embedded in LLM outputs and media.
- **Contributions:** Hardened the CLI and AST-level regex sanitizer (`#201`), added `--exclude` glob filters and batch processing (`#317`), built the pre-commit hook and GitHub Action workflow (`#328`), added `pyproject.toml` config support (`#338`), and delivered `.docx`/`.pdf` document watermark stripping (`#369`, `#371`, `#384`) with collaborator push access.

</td>
<td width="50%" valign="top">

### 🧠 [Knowledge-Agent](https://github.com/PrithvijitBose/Knowledge-Agent)
`PrithvijitBose/Knowledge-Agent` • <img src="https://img.shields.io/badge/Role-Contributor-131417?style=flat-square" alt="Contributor"/>

- **What it solves:** Hybrid vector-graph retrieval and autonomous local reasoning pipeline for knowledge agents.
- **Contributions:** Engineered multi-layer vector-graph query pipelines (`#28`–`#31`), local embedding index caching (`#35`, `#36`), deterministic citation grounding (`#41`, `#45`), and Windows/POSIX path normalization for cross-platform retrieval (`#49`).

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🕸️ [graphify](https://github.com/Graphify-Labs/graphify)
`Graphify-Labs/graphify` • <img src="https://img.shields.io/badge/Role-Contributor-131417?style=flat-square" alt="Contributor"/>

- **What it solves:** Turns multi-language codebases and markdown corpora into persistent, queryable knowledge graphs for AI coding agents.
- **Contributions:** Contributed to core AST extraction and community clustering (`#1824`), god-node detection heuristics, and multi-repository incremental graph rebuilds (`#3233`–`#3235`).

</td>
<td width="50%" valign="top">

### ⚡ [caveman](https://github.com/JuliusBrussee/caveman)
`JuliusBrussee/caveman` • <img src="https://img.shields.io/badge/Role-Contributor-131417?style=flat-square" alt="Contributor"/>

- **What it solves:** Token-efficient prompt compression and repository scanning for coding agents.
- **Contributions:** Engineered cross-platform hook and path normalization fixes (`#187`), Windows test-runner compatibility, and high-throughput monorepo scan heuristics.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 [oppia-web-developer-docs](https://github.com/oppia/oppia-web-developer-docs)
`oppia/oppia-web-developer-docs` • <img src="https://img.shields.io/badge/Role-Contributor-131417?style=flat-square" alt="Contributor"/>

- **What it solves:** Official developer onboarding, CI troubleshooting, and architecture documentation for Oppia Web.
- **Contributions:** Improved contributor setup verification and cross-platform developer environment documentation (`#527`, `#544`).

</td>
<td width="50%" valign="top">

### 🤖 [openbot](https://github.com/nightly-labs/openbot)
`nightly-labs/openbot` • <img src="https://img.shields.io/badge/Role-Contributor-131417?style=flat-square" alt="Contributor"/>

- **What it solves:** Modular autonomous agent runtime and tool execution harness.
- **Contributions:** Hardened tool-call validation and runtime error recovery in the agent execution loop (`#614`).

</td>
</tr>
</table>

<br/>

<div align="center">
  <a href="https://github.com/poorvith-mp?tab=repositories">
    <img src="https://img.shields.io/badge/Browse_All_Repositories_on_GitHub_%E2%86%92-08090b?style=for-the-badge&logo=github&logoColor=cda03a&color=131417" alt="Browse Repositories"/>
  </a>
</div>

---

## 📊 GitHub Streak & Technical Stack

<div align="center">

<!-- Streak Stats -->
<a href="https://github.com/poorvith-mp">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=poorvith-mp&theme=transparent&background=08090b&border=1f232b&stroke=cda03a&ring=cda03a&fire=cda03a&currStreakNum=eff0f1&sideNums=eff0f1&currStreakLabel=cda03a&sideLabels=eff0f1&dates=8e929a" alt="GitHub Streak" width="95%" />
</a>

<br/><br/>

### 🛠️ Technical Stack & Tools

| Layer | Technologies |
|---|---|
| **Languages & Runtimes** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| **Frontend & UI Systems** | ![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black) |
| **Edge & Cryptography** | ![Web Crypto API](https://img.shields.io/badge/Web_Crypto_API-cda03a?style=flat-square) ![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) |
| **AI Agent Ecosystem** | ![Model Context Protocol](https://img.shields.io/badge/MCP_Protocol-08090b?style=flat-square&logo=anthropic&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square) ![OpenAI Codex](https://img.shields.io/badge/Codex-412991?style=flat-square&logo=openai&logoColor=white) ![Antigravity](https://img.shields.io/badge/Google_Antigravity-4285F4?style=flat-square&logo=google&logoColor=white) |
| **Tooling & Quality** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white) |

</div>

---

## 🤝 Connect & Collaborate

<table width="100%">
<tr>
<td width="48%" align="center" valign="middle">

<!-- Profile Card Alt -->
<a href="https://poorvithmp.com">
  <img src="./assets/poorvith-profile-card-alt.jpg" width="100%" alt="Poorvith M P — Profile Card" />
</a>

</td>
<td width="52%" align="center" valign="middle">

<!-- Interactive Animated Collaboration Desk -->
<a href="mailto:contact@poorvithmp.com">
  <img src="./assets/connect-desk.svg" width="100%" alt="Engineering Collaboration Desk" />
</a>

</td>
</tr>
</table>

<br/>

<div align="center">
  <a href="mailto:contact@poorvithmp.com"><img src="https://img.shields.io/badge/Direct_Desk-contact@poorvithmp.com-cda03a?style=for-the-badge&logo=gmail&logoColor=white&labelColor=08090b" alt="Email Direct"/></a>
  <a href="https://poorvithmp.com"><img src="https://img.shields.io/badge/Visit_Portfolio-poorvithmp.com-131417?style=for-the-badge&logo=googlechrome&logoColor=cda03a&labelColor=08090b" alt="Website"/></a>
  <a href="https://linkedin.com/in/poorvithmp"><img src="https://img.shields.io/badge/LinkedIn-poorvithmp-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=08090b" alt="LinkedIn"/></a>
  <a href="https://x.com/poorvith_mp"><img src="https://img.shields.io/badge/Follow_X-@poorvith__mp-131417?style=for-the-badge&logo=x&logoColor=white&labelColor=08090b" alt="X"/></a>
  <a href="https://github.com/poorvith-mp?tab=repositories"><img src="https://img.shields.io/badge/Browse_Repositories-poorvith--mp-cda03a?style=for-the-badge&logo=github&logoColor=08090b&labelColor=08090b" alt="GitHub Repos"/></a>
</div>
