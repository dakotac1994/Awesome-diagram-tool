# Contributing to Awesome-diagram-tool

Thanks for helping keep this list accurate. This repo has strict honesty rules — please read them before opening a PR.

## What belongs here

- **Diagramming and visualization tools**: diagram-as-code (Mermaid, PlantUML, D2, Graphviz…), whiteboard/infinite-canvas tools (Excalidraw, tldraw, diagrams.net…), architecture & cloud diagram tools, mind-mapping tools, ERD/database diagram tools, sequence-diagram tools, and diagram **rendering libraries**.
- General graphic-design tools (Figma, Inkscape), BI dashboards, and charting libraries for data plots (matplotlib, D3) are **out of scope**.

## Entry requirements (all must hold)

1. **Real and verifiable.** The project must exist at the linked URL. `verified` is `true` only if you confirmed the entry on an official source (the project's repo, LICENSE file, or official site) — never from a blog roundup alone.
2. **Honest license.** Copy the SPDX identifier from the project's actual LICENSE file. Proprietary/freemium products (Miro, Lucidchart, GoJS…) are `"proprietary"` — never imply a paid product is open source. If the license can't be confirmed, set `"license": null`, `"verified": false`, and explain in `"unverified_reason"`.
3. **No invented facts.** No guessed star counts, pricing, or descriptions. If you can't verify it, leave it `null` and say why.
4. **One category each.** Pick the single best-fitting `category`.

## How to add an entry

1. Add the entry to `data/diagram-tools.json` (keep the file's existing ordering: grouped by category):
   ```json
   {
     "name": "Example Diagrams",
     "description": "One-line description, no hype.",
     "license": "MIT",
     "category": "diagram-as-code",
     "repo": "https://github.com/org/example-diagrams",
     "homepage": "https://example-diagrams.org",
     "official_site": "https://example-diagrams.org",
     "stars": 1234,
     "verified": true,
     "unverified_reason": null
   }
   ```
   Use `null` (not `""`) for unknown `repo`/`official_site`/`stars`/`unverified_reason`.
2. Add the matching bullet to the right section in `README.md`: `- [Example Diagrams](https://example-diagrams.org) — one-line description.`
3. Run the CI validation locally if you can (`python` 3.12+, see `.github/workflows/ci.yml`): it checks JSON validity, duplicate names/URLs, the README↔JSON cross-check, section counts, and TOC anchors.
4. Open a PR describing what you verified and where (link the official source).

## Link hygiene

- Prefer `https://` URLs; no URL shorteners.
- If a project renamed/moved, update to the canonical URL and note it in `docs/status-changes.md`.
- Commercial product links should point at official docs or pricing pages, not marketing landing pages, where possible.

## What gets rejected

- Entries with invented licenses, stars, pricing, or descriptions.
- Proprietary products presented as open source.
- Dead links, or projects you can't confirm exist.
