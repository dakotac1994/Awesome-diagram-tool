# Awesome Diagram Tool

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Entries](https://img.shields.io/badge/entries-60-blue)](data/diagram-tools.json)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated list of **diagramming and visualization tools**: diagram-as-code DSLs, whiteboard/infinite-canvas apps, architecture and cloud diagram tools, mind mappers, ERD/database diagrammers, sequence-diagram tools, and diagram rendering libraries.

> **Scope:** this list covers *diagramming tools* — things whose job is drawing diagrams. General graphic-design apps (Figma, Inkscape), BI dashboards, and data-plotting libraries (matplotlib, D3) are out of scope. Proprietary/freemium products are included but always explicitly labeled `"proprietary"` — this is a tools list, not an OSS-only list (contrast [awesome-oss-cli](https://github.com/dakotac1994/awesome-oss-cli)).
> **Honesty policy:** every entry was checked against an official source (project repo, LICENSE file, or official site) as of 2026-09-30 — **60/60 verified**. Unverified entries carry a stated reason. Proprietary products are explicitly labeled and never presented as open source. Machine-readable data lives in [`data/diagram-tools.json`](data/diagram-tools.json).

## Contents

- [Diagram as Code](#diagram-as-code) — 20 entries
- [Whiteboard & Canvas](#whiteboard--canvas) — 10 entries
- [Architecture & Cloud Diagrams](#architecture--cloud-diagrams) — 5 entries
- [Mind Maps](#mind-maps) — 5 entries
- [ERD & Database Diagrams](#erd--database-diagrams) — 10 entries
- [Sequence Diagrams](#sequence-diagrams) — 2 entries
- [Rendering Libraries](#rendering-libraries) — 8 entries

## Choosing the right diagram tool

New here? Start with the [choosing-a-diagram-tool](docs/choosing-a-diagram-tool.md) guide (text-based vs visual, collaboration, self-hosting, per-category picks), the [glossary](docs/glossary.md), and [status-changes](docs/status-changes.md) (renames, archival notices, license gotchas).

## Diagram as Code

Text-first diagrams that live in version control: write a DSL, get an SVG. The docs-and-PR workflow. (20 entries)

- [actdiag](http://blockdiag.com) — Generate activity-diagram image files from spec-text files. *(Apache-2.0 · ⭐ 34)*
- [blockdiag](http://blockdiag.com) — Generate block-diagram image files from spec-text files. *(Apache-2.0 · ⭐ 242)*
- [D2](https://d2lang.com) — D2 is a modern diagram scripting language that turns text into diagrams. *(MPL-2.0 · ⭐ 25,544)*
- [diagrams](https://diagrams.mingrammer.com) — Diagram as Code for prototyping cloud system architectures (Python). *(MIT · ⭐ 42,652)*
- [flowchart.js](http://flowchart.js.org/) — Draws simple SVG flowchart diagrams from a textual representation of the diagram. *(MIT · ⭐ 8,700)*
- [Graphviz](https://graphviz.org) — Graph visualization software: layout programs that render DOT-language graph descriptions into images and SVG. *(EPL-2.0 · ⭐ 1,473)*
- [Kroki](https://kroki.io) — Creates diagrams from textual descriptions via a unified API over many diagram tools. *(MIT · ⭐ 4,351)*
- [Markmap](https://markmap.js.org) — Build mindmaps with plain text (Markdown). *(MIT · ⭐ 13,139)*
- [Mermaid](https://mermaid.ai/open-source/) — Generate diagrams like flowcharts or sequence diagrams from text in a Markdown-inspired syntax. *(MIT · ⭐ 90,491)*
- [Mermaid CLI](https://github.com/mermaid-js/mermaid-cli) — Command-line tool (mmdc) that renders Mermaid diagrams to SVG, PNG or PDF. *(MIT · ⭐ 5,050)*
- [Mermaid Live Editor](https://mermaid.live) — Edit, preview and share Mermaid charts/diagrams in the browser. *(MIT · ⭐ 6,837)*
- [nomnoml](https://www.nomnoml.com) — The sassy UML diagram renderer: text to UML diagrams in the browser. *(MIT · ⭐ 2,837)*
- [nwdiag](http://blockdiag.com) — Generate network-diagram image files from spec-text files. *(Apache-2.0 · ⭐ 135)*
- [Pikchr](https://pikchr.org) — PIC-like diagram language by the SQLite author that renders diagrams to SVG. *(0BSD · ⭐ 155)*
- [PlantUML](https://plantuml.com) — Generate UML and other diagrams from textual descriptions (Java). *(GPL-3.0-or-later · ⭐ 13,346)*
- [PlantUML Server](https://plantuml.com/) — PlantUML online server: render diagrams on demand over HTTP. *(GPL-3.0-only · ⭐ 2,219)*
- [seqdiag](http://blockdiag.com) — Generate sequence-diagram image files from spec-text files. *(Apache-2.0 · ⭐ 75)*
- [Structurizr](https://docs.structurizr.com) — Models-as-code tooling for the C4 model: write Structurizr DSL to generate software architecture diagrams. *(Apache-2.0 · ⭐ 419)*
- [svgbob](http://ivanceras.github.io/svgbob-editor/) — Convert your ASCII diagram scribbles into happy little SVGs. *(Apache-2.0 · ⭐ 4,232)*
- [WaveDrom](https://wavedrom.com) — Digital timing diagram rendering engine (JSON waveform descriptions to SVG). *(MIT · ⭐ 3,503)*

## Whiteboard & Canvas

Infinite-canvas tools for sketching with humans — brainstorming, workshops, and freeform visual thinking. (10 entries)

- [diagrams.net](https://www.diagrams.net) — Free online diagramming app for flowcharts, UML, ERDs and more (formerly draw.io). *(Apache-2.0 · ⭐ 8,503)*
- [Eraser](https://www.eraser.io) — AI-powered diagramming tool that turns prompts, code and docs into production-ready diagrams. *(proprietary)*
- [Excalidraw](https://excalidraw.com) — Hand-drawn style virtual whiteboard for sketching diagrams and collaborating in real time. *(MIT · ⭐ 133,313)*
- [FigJam](https://www.figma.com/figjam/) — Figma's online collaborative whiteboard for brainstorming, planning and team workshops. *(proprietary)*
- [Lucidchart](https://www.lucidchart.com) — Intelligent diagramming platform for flowcharts, org charts, network and cloud diagrams. *(proprietary)*
- [Miro](https://miro.com) — Visual collaboration platform with an infinite canvas for workshops, diagrams and planning. *(proprietary)*
- [Mural](https://www.mural.co) — AI-powered visual workspace for team collaboration, workshops and design thinking. *(proprietary)*
- [Penpot](https://penpot.app) — Open-source design and prototyping platform with a collaborative vector canvas. *(MPL-2.0 · ⭐ 60,540)*
- [tldraw](https://tldraw.dev) — Infinite-canvas SDK and whiteboard for building collaborative drawing experiences in React. Custom tldraw license: free for dev/internal use, commercial license required for production (not OSI-approved). *(terms vary · ⭐ 50,675)*
- [Whimsical](https://whimsical.com) — Fast collaborative whiteboard for product teams with diagrams, wireframes and docs. *(proprietary)*

## Architecture & Cloud Diagrams

System architecture and cloud-infrastructure diagrams, from C4 models to auto-generated AWS/GCP views. (5 entries)

- [Cloudcraft](https://www.cloudcraft.co) — Live AWS/Azure/GCP architecture diagrams with cost and observability overlays (a Datadog product). *(proprietary)*
- [CloudMapper](https://github.com/duo-labs/cloudmapper) — Open-source AWS network topology diagrams and security audit reports. *(BSD-3-Clause · ⭐ 6,289)*
- [CloudSkew](https://cloudskew.com) — Online diagram and flowchart editor with built-in cloud provider icon libraries. *(proprietary)*
- [Holori](https://holori.com) — Multi-cloud architecture diagrams with cost estimation and Terraform export. *(proprietary)*
- [IcePanel](https://www.icepanel.io) — Collaborative C4 modeling and diagramming tool for software architecture. *(proprietary)*

## Mind Maps

Radial idea-mapping tools for brainstorming, outlining, and organizing thoughts. (5 entries)

- [Freeplane](https://www.freeplane.org) — Java mind mapping, knowledge management and project planning application. *(GPL-2.0 · ⭐ 4,390)*
- [Kinopio](https://kinopio.club) — Spatial thinking tool: connect images, text and links on an open canvas. *(PolyForm-Noncommercial-1.0.0 · ⭐ 885)*
- [MindMup](https://www.mindmup.com) — Pure, fast browser-based mind mapping with real-time collaboration. *(proprietary)*
- [MindNode](https://mindnode.com) — Native Apple mind mapping app for capturing and organizing ideas visually. *(proprietary)*
- [XMind](https://xmind.app) — Full-featured mind mapping and brainstorming app for desktop, web and mobile. *(proprietary)*

## ERD & Database Diagrams

Database schema visualization: entity-relationship diagrams, schema designers, and DB documentation. (10 entries)

- [ChartDB](https://chartdb.io) — Database diagram editor that visualizes and designs your DB from a single query. *(AGPL-3.0 · ⭐ 22,976)*
- [dbdiagram.io](https://dbdiagram.io) — Free online database designer for developers and analysts; schemas written in DBML (commercial freemium, paid tiers from $9/mo). *(proprietary)*
- [dbdocs](https://dbdocs.io) — Free database documentation web app and CLI from the makers of dbdiagram.io (DBML-based); a distinct product, not just a dbdiagram.io feature. *(proprietary)*
- [DBeaver ERD](https://dbeaver.io) — ER diagram viewer/editor built into the DBeaver universal database tool (entry covers DBeaver's ERD feature). *(Apache-2.0 · ⭐ 51,931)*
- [DrawDB](https://drawdb.app) — Free, simple online database diagram editor and SQL generator. *(AGPL-3.0 · ⭐ 39,812)*
- [erd](https://github.com/BurntSushi/erd) — CLI that translates a plain-text description of a relational schema into an ER diagram image. *(Unlicense · ⭐ 1,865)*
- [pgModeler](https://pgmodeler.io) — Open-source data modeling tool designed for PostgreSQL; generates DDL without hand-writing it. *(GPL-3.0 · ⭐ 3,602)*
- [QuickDBD](https://www.quickdatabasediagrams.com) — Online tool that draws database diagrams as you type a text-based schema (commercial freemium, Pro from ~$8/mo). *(proprietary)*
- [SchemaCrawler](http://www.schemacrawler.com/) — Free database schema discovery and comprehension tool; generates schema docs and diagrams. Bundled-JDBC-driver distributions are GPL-3.0. *(EPL-2.0 · ⭐ 1,836)*
- [tbls](https://github.com/k1LoW/tbls) — CI-friendly CLI tool to document a database, written in Go. *(MIT · ⭐ 4,353)*

## Sequence Diagrams

Time-ordered message-exchange diagrams for APIs, protocols, and system interactions. (2 entries)

- [WebSequenceDiagrams](https://www.websequencediagrams.com) — Web-based tool generating sequence diagrams from plain-text notation (commercial freemium, Pro from $15/mo). *(proprietary)*
- [ZenUML](https://zenuml.com/) — Free online tool turning text into UML sequence diagrams (ZenUML's open-source web app; repo actively maintained, pushed 2026-09-30). *(MIT · ⭐ 150)*

## Rendering Libraries

JavaScript libraries that render diagrams in the browser — for embedding diagrams in your own apps. (8 entries)

- [cytoscape.js](https://js.cytoscape.org) — Graph theory library for network visualization and analysis. *(MIT · ⭐ 11,229)*
- [dagre](https://github.com/dagrejs/dagre) — Directed graph layout engine for JavaScript. *(MIT · ⭐ 5,808)*
- [elkjs](https://github.com/kieler/elkjs) — Eclipse Layout Kernel (ELK) layout algorithms for JavaScript. *(EPL-2.0 OR GPL-3.0-or-later · ⭐ 2,793)*
- [GoJS](http://gojs.net) — JavaScript diagramming library for interactive flowcharts, org charts and visual languages (proprietary, by Northwoods Software). *(proprietary · ⭐ 8,484)*
- [JointJS](https://jointjs.com) — SVG-based JavaScript diagramming library for building interactive diagram UIs. *(MPL-2.0 · ⭐ 5,392)*
- [vis-network](https://visjs.github.io/vis-network/) — Library for dynamic, automatically organized, customizable network views. *(Apache-2.0 · ⭐ 3,631)*
- [visx](https://visx.airbnb.tech) — Airbnb's collection of low-level visualization components for React. *(MIT · ⭐ 21,071)*
- [xyflow](https://xyflow.com) — Powerful open-source libraries for node-based UIs: React Flow and Svelte Flow (the react-flow org renamed to xyflow). *(MIT · ⭐ 38,555)*

## Notable exclusions

Candidates that were researched and deliberately left out:

| Excluded | Reason |
| --- | --- |
| FreeMind | Dormant since 2014; development continued by the fork Freeplane (listed). |
| Structurizr Lite | Archived by the maintainer; product discontinued in favor of consolidated Structurizr tooling. |
| plantuml-github-action | No such repo under the PlantUML org (404); community actions exist but aren't official. |
| D2 playground | Closed-source web app; no confirmable license. |
| tk0miya/* blockdiag repos | Superseded stubs after the move to the `blockdiag/*` org (listed). |
| drj11/pikchr | Dead stub; canonical mirror is `drhsqlite/pikchr`, home is pikchr.org. |
| kroki/kroki | 404; canonical repo is `yuzutech/kroki` (listed). |
| github.com/graphviz/graphviz | Archived 4-star stub; the real project lives on GitLab. |
| mermaid.js | Same project as Mermaid (listed), not a distinct entry. |
| eraser-dev/eraser | Unrelated Kubernetes image-cleaning tool — a name collision with the Eraser whiteboard SaaS (listed). |
| ZenUml/ZenUml | Org issue-tracker repo with no code; the app is `ZenUml/web-sequence` (listed). |
| elkjs/elkjs | Wrong org; the Eclipse ELK JS project is `kieler/elkjs` (listed). |

## Related

More curated lists by the same author:

- [Awesome-terminal](https://github.com/dakotac1994/Awesome-terminal) — terminal emulators and the terminal stack.
- [awesome-cli](https://github.com/dakotac1994/awesome-cli) — the broad CLI/TUI tools list.
- [awesome-oss-cli](https://github.com/dakotac1994/awesome-oss-cli) — the OSS-only CLI/TUI list.
- [awesome-oss-macos](https://github.com/Awesome-llms-labs/awesome-oss-macos) — open-source macOS apps.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). PRs welcome — every entry must be verified against an official source, with the license copied from the project's actual LICENSE file.
