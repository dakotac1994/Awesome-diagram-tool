# Glossary

Terms you'll meet across the [Awesome-diagram-tool](../README.md) catalog.

- **Diagram-as-code** — writing diagrams in a text-based DSL that renders to an image/SVG, so diagrams live in version control next to code (Mermaid, PlantUML, D2, Graphviz DOT).
- **DSL (domain-specific language)** — the small text language a diagram-as-code tool parses (e.g. Mermaid's flowchart syntax, Graphviz's DOT, D2's layout language).
- **DOT** — Graphviz's graph description language; the oldest widely-used diagram DSL (`.dot` / `.gv` files).
- **Mermaid** — the Markdown-adjacent diagram DSL (flowcharts, sequence, ER, Gantt…) with the widest renderer support.
- **PlantUML** — text-to-UML tool with its own syntax covering sequence, class, activity, and more diagrams.
- **D2** — a modern diagram DSL with automatic layout, positioned as a friendlier successor to Graphviz/Mermaid for software diagrams.
- **Kroki** — a unified API/server that renders many diagram DSLs (Mermaid, PlantUML, Graphviz, D2…) behind one endpoint.
- **Infinite canvas** — a zoomable, unbounded drawing surface (Excalidraw, tldraw, Miro); the whiteboard paradigm.
- **Whiteboard** — a freeform collaborative drawing surface; real-time multi-user editing is the headline feature.
- **Sticky notes** — the movable text cards that anchor whiteboard brainstorming; most canvas tools treat them as first-class objects.
- **Wireframe / mockup** — low-fidelity UI sketches; some diagram tools double as wireframing surfaces.
- **UML (Unified Modeling Language)** — the standardized family: class, sequence, activity, state, use-case, component, deployment diagrams.
- **Sequence diagram** — time-ordered message exchange between participants (lifelines); the core of API/protocol documentation.
- **ERD (entity-relationship diagram)** — tables, columns, keys, and relationships; the standard way to draw a database schema.
- **C4 model** — Simon Brown's hierarchical architecture notation: Context → Container → Component → Code; Structurizr is built around it.
- **Architecture diagram** — boxes-and-arrows views of systems, services, and cloud resources (often auto-generated from IaC).
- **Mind map** — a radial tree of ideas branching from a central topic; the brainstorming/outlining format.
- **Flowchart** — decision/process boxes connected by arrows; the oldest diagram genre.
- **BPMN** — Business Process Model and Notation; the XML-backed standard for process diagrams (bpmn-js renders it).
- **SVG** — Scalable Vector Graphics; the crisp, zoomable export format every diagram tool should offer.
- **Layout engine** — the algorithm that positions nodes/edges automatically (dagre, ELK, D2's engine); what separates diagram tools from drawing tools.
- **DAG (directed acyclic graph)** — the graph shape most auto-layout engines target: nodes with directed edges, no cycles.
- **Node / edge** — the graph primitives: a box (node) and a connector (edge).
- **Self-hosting** — running the tool on your own infrastructure (Excalidraw+, diagrams.net, Kroki, Structurizr Lite support it); matters for private diagrams.
- **Real-time collaboration** — multiple cursors editing the same canvas/document simultaneously (tldraw, Excalidraw, Miro, FigJam).
- **Freemium** — free tier with paid upgrades; most proprietary canvas tools in this list use it — labeled, never implied open source.
- **Export formats** — PNG/SVG/PDF/Markdown export; diagram-as-code tools usually emit SVG natively.
- **Version control for diagrams** — text-based diagrams diff and merge like code; canvas tools need explicit version history instead.
- **Rendering library** — a JS library that draws diagrams in the browser (react-flow/xyflow, cytoscape.js, jointjs) rather than a standalone app.
