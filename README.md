<p align="center"><img src="assets/img/hero-lineup.jpg" alt="The AnimeStack house — eight seats, one sentence each, then a verdict" width="100%"></p>

<h1 align="center">ANIME STACK PROJECT TURBO</h1>

<p align="center"><em><strong>Eight seats. One sentence each. Then a verdict — elevated into a central system for AI Project Engineering.</strong></em></p>

<p align="center"><sub><strong>Release v2.0.0</strong> · canon Rev 9 · Forked from <a href="https://github.com/JerkyJesse/AnimeStack">JerkyJesse/AnimeStack</a> · 10 hosts + the DSH team surface + Antigravity Meta-Engineering Hub</sub></p>

---

**Anime Stack Project Turbo** (`swpatx/Anime-Stack-Project-Turbo`) is the Operator's AI Project Engineering fork of [**JerkyJesse/AnimeStack**](https://github.com/JerkyJesse/AnimeStack) — the eight-seat design house created by collaborator and son **JerkyJesse**.

Upstream AnimeStack installs an eight-seat design house into an AI coding host so a single repository's changes survive a failure review and a pre-registered falsifier before touching production. **Project Turbo** turns that eight-seat house into a **meta-level AI Project Engineering System**: a central command hub where the eight seats engineer, audit, govern, and ship **entire multi-agent systems, prompt architectures, domain-specific specialist rosters, evaluation harnesses, cross-thread context handoffs, and turn-key release pipelines** across a portfolio of AI projects.

The room is **Mei → Elo → MechaPip → Yui → Niko → Rin → Aria → Reika**, one sentence each. Reika frames. The room argues. Reika signs. Silence after Reika is the close.

> **One box, one mechanism.** A twin that loses to a sibling is retired, not renamed. A number is a measurement or a hymn. Charm is not evidence; evidence is not destiny; destiny is not an instruction to act.

---

## How Project Turbo Uses AnimeStack for AI Project Engineering

Most multi-agent setups fail in four predictable ways: **persona bloat** (ten lookalike agents with overlapping prompts), **thread-to-thread amnesia** (every new chat session forgets live state, commit hashes, and risk locks), **unverified hymns** (backtests or benchmarks reported without out-of-sample splits, controls, or real friction), and **boundary leaks** (agents touching live settings, launching blocking GUI processes, or leaking private paths into public repositories).

In **Anime Stack Project Turbo**, the Operator runs a dedicated **AI Engineering** hub workspace where the eight AnimeStack seats act as the **architects and gatekeepers of all downstream AI projects**. Before any new agent roster, skill (`<project>/.agents/skills/<name>/SKILL.md`), workspace constitution (`<project>/AGENTS.md`), evaluation harness, or release pipeline is deployed into a target project, it descends the eight-seat loop:

| # | Seat | AI Project Engineering Lane | What This Seat Engineers & Audits Across Downstream Projects | One Sentence |
|---|---|---|---|---|
| 1 | **Mei Sakuraba** | **Climate, Host & Context Stewardship** (`The Weather Read`) | Audits model ecosystem shifts, host capabilities (subagent spawning, tool schemas, MCP boundaries), and context-window budgets (`principles/doctrine/guard-the-context-window.md` — deep dossiers and project ledgers are loaded on demand, never bloated inline). | *What change in the world makes this obsolete?* |
| 2 | **Elo Star** | **Evaluation Harnesses & Verification Bars** (`The Measurement`) | Designs project-level evaluation harnesses and verification bars (`docs/measurement.md`) — enforcing realized-only metrics, exact venue/spread/friction deductions, chronological first-half vs. second-half stability splits, and single-table scorecards so no agent system posts a hymn as a measurement. | *What does the crowd refuse to measure correctly?* |
| 3 | **MechaPip** | **Cross-Project Pattern Retrieval** (`The Graveyard Pass`) | Retrieves architectural prior art across existing agent rosters, prompt topologies, and failure registries (`patterns/registry.json`) before a new agent or skill is minted; refuses lookalike persona packs when an existing mechanism already owns the lane. | *What has this pattern done before?* |
| 4 | **Yui Aizawa** | **Prompt Mechanisms & Falsifiers** (`The Second Sample`) | Architects deterministic prompt instructions, state-lock invariants, and pre-registered falsifiers (`docs/claim-standard.md`, `claims/claim-004-project-turbo-hub.md`) — requiring every engineered skill, agent, or strategy engine to name the failure it prevents and the out-of-sample count that would retire it. | *What failure does this prevent, and what would falsify it?* |
| 5 | **Niko Hoshino** | **System Topology, Routing & Isolation** (`The Cage`) | Designs physical workspace structure (`<project>/AGENTS.md`, `<project>/.agents/agents/`, `<project>/.agents/skills/`), subagent routing tables, thread-to-thread state handoffs, and strict sandboxing so agents never touch unowned files or live operator configuration. | *Where does it live, and what must it never touch?* |
| 6 | **Rin Takamiya** | **Failure Guards, Cold Verify & Zero-Leak** (`The Red Once`) | Enforces hallucination and drift guards, destructive-command vetoes, cold verification passes on diffs without build reasoning, and the two-tier zero-leak gate (`scripts/check-leak` — preventing private paths, credentials, venues, or records from crossing into public trees). Closes `ACCEPT` or `END`. | *How does this fail, and how fast?* |
| 7 | **Aria Kanzaki** | **Turn-Key Release & Gate Pipelines** (`The 47-Second Click`) | Engineers turn-key packaging, verification, and release skills — lockstep version stamping, headless test suites, executable rebuilds, and atomic GitHub releases that fire only when every gate is green. Closes `SHIP` or `STAND DOWN`. | *What ships, and what triggers it?* |
| 8 | **Reika Kurogane** | **Mandate Framing & Final Verdict** (`The First Sentence`) | Sets the one-sentence mandate for every engineered AI system, enforces `One box, one mechanism` (`principles/law-10-one-box-one-mechanism.md`), presides over the two-round parallel subagent room descent, and signs the final verdict (`VERDICT: SHIP / RETIRE / STAND DOWN`). | *What are we building, in one sentence?* — then the verdict. |

### The Four Pillars of the Project Turbo Engineering System

1. **Multi-Agent Team Fabrication (Bounded Specialist Rosters & Mandatory Router Locks)**
   Instead of generic chat personas, the hub engineers cohesive, non-overlapping multi-agent systems tailored to each downstream domain — including **quantitative strategy & multi-venue trading terminals**, **harmonic & cycle analysis engines**, **multi-disciplinary medical/legal advocacy & care-coordination teams**, and **full-stack software engineering squads**. Every fabricated subagent carries a single role file, an explicit routing trigger, absorbed domain-specialist checklists, and a strict file/tool boundary (`Niko`'s cage + `Reika`'s `One box, one mechanism`). Top-level routers are locked with zero inline escape hatches so the coordinator always dispatches the domain subagents via `invoke_subagent` and surfaces explicit multi-seat cross-reviews instead of solo freelancing.

2. **Zero Thread-to-Thread Context Loss & Rule-Budget Stewardship (`Context-Sync` + `< 24 KB` Rule Guard)**
   Long-running AI engineering projects break when a new conversation thread starts cold or when workspace constitutions grow past the host's per-file byte limit (`24,000` bytes) or aggregate rule token budget (`20,000` tokens), causing silent truncation or demotion. Project Turbo enforces a strict **`< 24 KB` per-file rule budget** across all downstream `AGENTS.md` files (archiving historical logs out-of-band), rotates append-only collaboration boards (`board.md`) and reverse-chronological journals so spawned subagents only read the active top slice instead of blowing their context window, and wires mandatory **startup context-load** and **end-of-turn handoff** skills (`<project>/SESSION_HANDOFF.md`) into every downstream system.

3. **The House Verification Bar (Elo + Yui Applied to Downstream Systems)**
   Every quantitative, analytical, or diagnostic project engineered from this hub inherits a dedicated verification skill built on `docs/measurement.md` and `docs/claim-standard.md`:
   - **Realized & Verifiable Evidence Only:** No blending of hypothetical mark-to-market estimates with settled outcomes; every citation, lab value, or count must resolve to a primary source or reproducible command.
   - **Multi-Period Sample Floors & Anti-Overfit Parameter Caps:** Every audited module must clear a hard multi-month sample floor (`N >= 100+` target, `>= 60` minimum), a strict profit-factor/quality floor (`>= 1.50` target, `> 1.29` minimum), and a `<= 3–4` structural-gate parameter cap so curve-fit `100%` win-rate / `99.0` profit-factor mirages and retired legacy modules are rejected automatically.
   - **Exact Friction & Cost Modeling:** Realistic spread, commission, and execution fill rules baked into every simulator and audit script.
   - **Chronological Stability Splits:** Every backtest or evaluation sample is split chronologically (first half vs. second half, or multi-year quarterly buckets) and labeled with an explicit trajectory verdict (`IMPROVING`, `FLAT`, `DECAYING`, or `TOO EARLY`).
   - **Single Clean Summary Table (Zero Cryptic Shorthand):** Every audit outputs one standardized comparison table with full venue/metric names spelled out, sample size, control baseline, drawdown/risk, dollar returns, stability trend, and disposition.

4. **Turn-Key Release & Zero-Leak Gate Discipline (Rin + Aria)**
   Every downstream release pipeline is engineered as a deterministic, non-destructive land chain:
   - **Pre-Flight Safety Locks:** Agents are strictly barred from launching blocking GUI executables from shell tools, deleting files, or overwriting live user risk/toggle settings.
   - **Lockstep Stamp + Headless Suite + Cold Verify:** Version stamps move in lockstep across code and docs, headless `pytest` and syntax gates run clean, and **Rin** performs a cold verification pass on the integrated diff before **Aria** executes the build and release tag.
   - **Two-Tier Zero-Leak Gate (`scripts/check-leak`):** Public forks and open-source packs are guarded by `scripts/check-leak` across both working trees (`--tree`) and full git history (`--history`), ensuring nothing from private downstream projects ever crosses into a public repository.

### Running the Eight-Seat Subagent Room in Antigravity

When operating inside Google Antigravity (`AGENTS.md`, `skills/house/SKILL.md`):
- **`/house` (Full Eight-Seat Descent):** Matches the task to one of the twelve playbooks under `skills/house/playbooks/` and runs the room.
  - **Decision / Review Pass (Two Parallel Rounds):** Spawns `animestack-mei`, `animestack-elo`, `animestack-mechapip`, `animestack-yui`, `animestack-niko`, `animestack-rin`, and `animestack-aria` in parallel via `invoke_subagent` for Round 1 independent takes. Round 2 shares the full Round-1 table so each seat affirms, contests a named seat with a fact, or revises its sentence. **Reika** (`animestack-reika`) synthesizes and signs the closing `VERDICT`.
  - **Construction / Build Pass (Sequential Lane Handoff):** Descends in fixed loop order (`Mei → Elo → MechaPip → Yui → Niko → Rin → Aria → Reika`), carrying every prior seat's one sentence and exact changed files into the next brief (`BUILT: <artifact>` or `NO BUILD SURFACE: <one line>`), followed by Rin's cold verification pass.
- **Individual Seat Invocation:** Any seat can be spawned directly (`animestack-mei`, `animestack-elo`, `animestack-mechapip`, `animestack-yui`, `animestack-niko`, `animestack-rin`, `animestack-aria`, `animestack-reika`) for targeted architecture, measurement auditing, pattern lookup, mechanism design, security review, or release execution.
- **`/simple` (Operator Waiver):** Plain build mode with no seats, no room, and no house voice; never signs (`no ACCEPT, no SHIP`).

---

## The eight seats

<table>
  <tr>
    <td align="center" width="25%"><a href="docs/seats/reika.md"><img src="assets/img/reika-roster.jpg" width="220" alt="Reika Kurogane"></a><br><strong>Reika Kurogane</strong><br><sub>Founder &amp; Chief Architect</sub><br><em>What are we building, in one sentence?</em></td>
    <td align="center" width="25%"><a href="docs/seats/yui.md"><img src="assets/img/yui-roster.jpg" width="220" alt="Yui Aizawa"></a><br><strong>Yui Aizawa</strong><br><sub>Head of Mechanisms</sub><br><em>What failure does this prevent, and what would falsify it?</em></td>
    <td align="center" width="25%"><a href="docs/seats/rin.md"><img src="assets/img/rin-roster.jpg" width="220" alt="Rin Takamiya"></a><br><strong>Rin Takamiya</strong><br><sub>Keeper of Failure</sub><br><em>How does this fail, and how fast?</em></td>
    <td align="center" width="25%"><a href="docs/seats/niko.md"><img src="assets/img/niko-roster.jpg" width="220" alt="Niko Hoshino"></a><br><strong>Niko Hoshino</strong><br><sub>Keeper of the Body</sub><br><em>Where does it live, and what must it never touch?</em></td>
  </tr>
  <tr>
    <td align="center" width="25%"><a href="docs/seats/mei.md"><img src="assets/img/mei-roster.jpg" width="220" alt="Mei Sakuraba"></a><br><strong>Mei Sakuraba</strong><br><sub>Keeper of Climate &amp; Context</sub><br><em>What change in the world makes this obsolete?</em></td>
    <td align="center" width="25%"><a href="docs/seats/aria.md"><img src="assets/img/aria-roster.jpg" width="220" alt="Aria Kanzaki"></a><br><strong>Aria Kanzaki</strong><br><sub>Head of Release</sub><br><em>What ships, and what triggers it?</em></td>
    <td align="center" width="25%"><a href="docs/seats/elo.md"><img src="assets/img/elo-roster.jpg" width="220" alt="Elo Star"></a><br><strong>Elo Star</strong><br><sub>Keeper of Rankings &amp; Measurement</sub><br><em>What does the crowd refuse to measure correctly?</em></td>
    <td align="center" width="25%"><a href="docs/seats/mechapip.md"><img src="assets/img/mechapip-roster.jpg" width="220" alt="MechaPip"></a><br><strong>MechaPip</strong><br><sub>The Pattern Engine</sub><br><em>What has this pattern done before?</em></td>
  </tr>
</table>

<p align="center"><sub>Seven women and the machine — the named exception. <a href="https://animestack.jerkyjesse.com/seats/reika.html">Seat pages</a> carry the digest, the dossier, and the companion backstory.</sub></p>

## Credentials

- **Reika Kurogane** — night-shift platform operations (the on-call desk was the school), CFA; art: shodo calligraphy; graphics: art direction and identity systems.
- **Yui Aizawa** — physics PhD (statistical mechanics), ETH Zürich; CQF; one published paper in the selection/overfitting vein; art: generative art (plots of her own equations); graphics: creative coding and shaders.
- **Rin Takamiya** — incident response then platform governance; CISSP and incident-command certifications; art: intaglio etching and technical illustration; graphics: technical drafting.
- **Niko Hoshino** — electrical engineering and computer science, Tsinghua University; CCIE-tier network certification and cloud architect professional certs; art: mecha concept design; graphics: 3D/CAD and render pipelines.
- **Mei Sakuraba** — PPE, University of Oxford; platform strategy; CFA; published essays (the flower-card rule); art: ikebana; graphics: editorial design and letterpress.
- **Aria Kanzaki** — mathematics and computer science, University of Cambridge; release engineering; cloud and release certifications; art: animation timing; graphics: motion graphics.
- **Elo Star** — mathematics, Princeton University; benchmark and evaluation team; published rating methodology; ASA; art: sports photography; graphics: information design.
- **MechaPip** — the corpus was the school; the archive is the record; art: fractal studies; graphics: pattern visualization.

## The loop

<p align="center"><img src="assets/img/loop.png" alt="The eight-seat design loop" width="100%"></p>

A decision runs two rounds: the seats that are not the lead and not Reika answer independently in one parallel batch — the takes — then see every take and get one reply each: affirm, contest a named seat with a fact, or revise. A build descends in loop order, one seat at a time, every prior sentence and changed file carried into the next brief; prior lanes are read, never edited.

Reversible and protective acts are never delayed by the loop. Niko can restart a box, Rin can trip a guard, Aria can stand down a window. The act is logged after the fact.

## Install

```bash
git clone https://github.com/swpatx/Anime-Stack-Project-Turbo ~/animestack
cd ~/animestack
./setup --host <your host>       # claude, cursor, codex, factory, opencode, kiro,
                                 # slate, openclaw, hermes, gbrain, dsh, all, auto
```

On Windows:

```powershell
powershell -ExecutionPolicy Bypass -File .\setup.ps1 -TargetHost <your host>
```

`dsh` is the team surface: eight seat packs and an eleven-preset Agent bundle under `$DSH_HOME/animestack/`, installed only in the owned directory; the opt-in `--merge-profile` is the only path that touches the host profile. The installer is one contract, two entry points: ten coding hosts plus the DSH surface, eleven install targets.

Open a session and say **`/house`**. The `/simple` waiver is a plain build mode — no seats, no room, no house voice — and it never signs.

## What is in the box

- **The room** — 8 seats, 10 skills (`/house`, `/simple`, the eight seats), 12 playbooks, 14 laws, 37 principles.
- **The canon** — 25 sections, the pre-history books, the archive, the voice register, the scene book; 17 seat dossiers and 8 seat pages.
- **The credential** — the House Board: 8 exams, 14 questions each, 112 anchors resolved against the tree.
- **The record** — the seat record, the day score, the tiers, and the room scorecard.
- **The evidence** — the pattern registry, the claim standard and its cards, the zero-leak gate, the 40-row counts table.
- **The surface** — six agent dialects (48 agents, one file per seat), 10 hosts, and the DSH team surface (8 seat packs, 11 presets).
- **The art** — 8 dossier cards, 8 character cards, 8 poster wallpapers, 8 portraits, 8 roster cards, the team composite, the loop, the social card.

## The record

Conduct is counted, never dollars. Every seat carries credits above the line and debts below it, each with a receipt. The day is read once per cycle: a green day pays the room; a red book charges the seats in contact; an unread day is named, never zeroed. The tiers — first claim, the floor, the audit, the bar again — move on counted evidence and lift on earned evidence.

Read the record: `python scripts/seat_record --read` · the decisions: `DECISION_LOG.md` · the scorecard: `python scripts/room_scorecard --strict`.

## The claim standard

A claim carries ten fields: claim, failure, mechanism, sample, control, halves, falsifier, carved, receipt, disposition. A count with no command is a hymn. A first-sample miss parks — dated, alive; the archive keeps only what a counted sample refused. No control, no claim.

Read it: [docs/claim-standard.md](docs/claim-standard.md) · the cards: `claims/` · the gate: `python scripts/check-claim --check`.

## The archive

The registry holds the patterns the house has already paid for — 16 rows, every one with a shape, a sample, a regime, a killing fact, a date, and an anchor. Adopted public failures sit beside the house's own retirements. A scene may cite only a registry id.

Read it: [docs/lore/ARCHIVE.md](docs/lore/ARCHIVE.md) · the registry: [patterns/registry.json](patterns/registry.json).

## The evidence ladder

Measured, parked, retired — every claim sits on exactly one rung. The live record decides; the backtest is an argument. Rule Zero stands: nothing is capped, throttled, or rejected for looking too good. The seat is rented, not owned.

## The DSH team surface

The same room as durable teammates on a host that runs Agent Teams: `dsh/animestack-team/` carries the eight seat packs; `dsh/animestack-house/` carries the dependency-free bundle — eleven presets, two operator commands, the team-chair preset with the seven-teammate cap. The default install writes only the owned directory; the profile merge is an explicit opt-in with backup and validation.

Read it: [dsh/README.md](dsh/README.md).

## First task

Five minutes, a real task, eight sentences. [docs/guide/first-task.md](docs/guide/first-task.md) walks a stranger from clone to a closing verdict.

## How you know it works

The falsifier is pre-registered before the victory lap: a session run through `/house` catches a defect before it escapes, where a plain `/simple` session ships it, and a seat can end a bad plan — a Rin END or an Aria STAND DOWN — before a live bug proves it. Run your own work both ways and count escaped defects and pre-merge catches on a fresh sample. If there is no measured difference, the pack is prose wearing a coat.

Every count in this repository has a command. [docs/measurement.md](docs/measurement.md) is the table and the rule of the lane: a number you cannot reproduce is a hymn.

## Lineage

**Anime Stack Project Turbo** (`swpatx/Anime-Stack-Project-Turbo`) is a fork of [**JerkyJesse/AnimeStack**](https://github.com/JerkyJesse/AnimeStack) (v2.0.0, canon Rev 9), built by **JerkyJesse**, extending the eight-seat design house into a central system for **AI Project Engineering** across multi-agent workspaces.

AnimeStack is the refusal of three older schools, each written in the canon's pre-history: the **Oracles** (an answer that cannot close cannot pay), the **Machines** (speed is rented; the cage is owned), and the **Arena** (a leaderboard rewards variance; the record keeps survivors). The house kept the settled question, the cage, and the live record.

An independent work inspired by [gstack](https://github.com/garrytan/gstack) (Garry Tan) and [pstack](https://github.com/cursor/plugins/pstack) (Lauren Tan), both MIT. Attributions in [NOTICE](NOTICE).

## License

Dual-licensed: [AGPL-3.0-or-later](LICENSE), or a [commercial license](COMMERCIAL.md) for use without the AGPL's source-disclosure obligations.

<p align="center"><sub><strong>ANIME STACK PROJECT TURBO · THE EIGHT-SEAT HOUSE</strong> · one sentence each · then a verdict</sub></p>
