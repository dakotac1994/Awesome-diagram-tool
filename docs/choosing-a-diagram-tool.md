# Choosing the right diagram tool

Start from how you want to *author* the diagram, then from who needs to *read* it.

## Text-based or visual?

- **Diagram-as-code** (Mermaid, PlantUML, D2, Graphviz) if the diagram must live in version control, be reviewed in PRs, and regenerate from CI. Downsides: less freeform, layout is the engine's job.
- **Whiteboard / canvas** (Excalidraw, tldraw, diagrams.net, Miro) if you're sketching with humans — brainstorming, workshops, ad-hoc architecture discussions. Downsides: binary formats, weaker diffing.

Rule of thumb: docs and runbooks → diagram-as-code; meetings and ideation → canvas.

## Collaboration

- **Real-time multi-user**: tldraw, Excalidraw (+), Miro, FigJam, Lucidchart. If it's a workshop tool, this is non-negotiable.
- **Async / review-based**: diagram-as-code in git (any renderer), diagrams.net files in a repo.

## Self-hosting and privacy

If diagrams contain private architecture, self-host: Excalidraw and tldraw are MIT and self-hostable; diagrams.net has a desktop build; Kroki and Structurizr Lite run on your own infra; D2/Graphviz/PlantUML render locally with no network at all. Proprietary canvas tools are cloud-first by design.

## Which diagram-as-code tool?

- **Mermaid** — the default for Markdown docs; the DSL everyone already knows; weakest auto-layout of the modern options.
- **D2** — the best-looking software diagrams with the least fiddling; strong auto-layout; newer ecosystem.
- **PlantUML** — the UML specialist (sequence, class, activity); verbose syntax, unmatched UML coverage.
- **Graphviz** — the venerable graph layout engine; best when you need DOT's layout algorithms, weakest as an authoring experience.
- **Kroki** — not a DSL but a renderer: one server/API for all of the above; ideal for docs pipelines.

## Which canvas?

- **Excalidraw** — hand-drawn aesthetic, MIT, self-hostable; the open-source default.
- **tldraw** — the developer's canvas: best-in-class SDK if you're *building* a whiteboard into your product.
- **diagrams.net** — the structured-diagram workhorse (flowcharts, network, ERD); desktop + web, free.
- **Miro / FigJam / Lucidchart** — proprietary, paid, and the best real-time collaboration; pick when the whole company needs to be on one board.

## Specialized needs

- **Software architecture (C4)**: Structurizr / Structurizr Lite — the DSL is the model, diagrams are views.
- **Cloud diagrams**: IcePanel, Cloudcraft, Holori, CloudSkew — AWS/GCP/Azure icon sets and cost overlays.
- **Database schemas**: dbdiagram.io / DrawDB / ChartDB for quick ERDs; pgModeler for serious Postgres modeling.
- **Mind maps**: XMind / MindNode for polished maps; Freeplane when you want free and offline.
- **Embedding diagrams in your app**: react-flow (xyflow), cytoscape.js, jointjs, mermaid.js — libraries, not apps.

## Licensing notes

Every entry in this list was checked against an official source as of 2026-09-30. Proprietary tools are explicitly labeled `"proprietary"` — this is a curated *tools* list, not an OSS-only list (contrast [awesome-oss-cli](https://github.com/dakotac1994/awesome-oss-cli)). If you need strictly open source, filter `data/diagram-tools.json` for entries whose `license` is an SPDX id rather than `"proprietary"`.
