# Status Changes

Notable renames, archival notices, dormancy, and license gotchas affecting entries in this list. Last reviewed 2026-09-30.

## Renames / moves

- **draw.io → diagrams.net** — the same product rebranded; `draw.io` redirects to `diagrams.net`. Entries use the canonical `diagrams.net` name (repo still `jgraph/drawio`).
- **react-flow → xyflow** — the project/org renamed to xyflow; the library is still published as React Flow. Entries use the current canonical naming.
- **Mermaid Live Editor** — the official live editor is at `mermaid.live`.
- **Blockdiag family: `tk0miya/*` → `blockdiag/*`** — blockdiag, seqdiag, actdiag, nwdiag moved to the `blockdiag/*` org; old repos are dead stubs.
- **Kroki: `kroki/kroki` (404) → `yuzutech/kroki`** — canonical repo is under yuzutech.
- **Pikchr: `drj11/pikchr` (404) → `drhsqlite/pikchr`** — official GitHub mirror under D. Richard Hipp's account; canonical home is pikchr.org (Fossil).
- **Graphviz: GitHub → GitLab** — `github.com/graphviz/graphviz` is an archived stub; the real repo is `gitlab.com/graphviz/graphviz`.
- **Cloudcraft → Datadog** — Cloudcraft is now a Datadog product ("DD by Cloudcraft" branding).
- **Structurizr consolidation** — the archived `structurizr/java` and `structurizr/cli` repos are superseded by the consolidated `structurizr/structurizr` repo.

## Archived / dormant

- **Structurizr Lite** — archived by the maintainer; product discontinued. Excluded from the list.
- **FreeMind** — dormant since 2014; development continued by the fork Freeplane (listed).
- **CloudMapper** — not archived but dormant (last push 2024-07); kept with the caveat in its description.
- **flowchart.js** — low-activity legacy code (not archived); kept as a historical entry.

## License gotchas (verified on official sources)

- **PlantUML** — default license is **GPL-3.0-or-later** (GitHub's detector says LGPL-3.0, but the LICENSE file is plain GPL-3.0; optional LGPL/Apache/MIT/BSD/EPL variants exist via subprojects).
- **DrawDB / ChartDB** — **AGPL-3.0** (not MIT/GPL).
- **SchemaCrawler** — **EPL-2.0** (SPDX identifier in source headers); distributions bundled with JDBC drivers ship as GPL-3.0-only.
- **elkjs** — **EPL-2.0 OR GPL-3.0-or-later** (dual expression from package.json).
- **tldraw** — custom tldraw license: free for dev/internal use, commercial license required for production; **not OSI-approved** (recorded as `license: null` with the caveat in the description).
- **Kinopio** — **PolyForm-Noncommercial-1.0.0** (noncommercial; not open source in the OSI sense).
- **GoJS** — proprietary (Northwoods Software License Agreement).
- **DBeaver ERD** — a feature of DBeaver, not a separate product; stars/license shown are the parent repo's, stated in the description.

## Product / naming notes (2026-09-30)

- **diagrams.net vs drawio desktop** — same product, web vs desktop builds; listed once.
- **dbdiagram.io / dbdocs** — same company (Holistics) but genuinely distinct products (designer vs documentation/CLI); listed separately, both proprietary.
- **ZenUML** — the app is `ZenUml/web-sequence`; `ZenUml/ZenUml` is just the org issue tracker.
