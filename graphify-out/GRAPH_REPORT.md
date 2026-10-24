# Graph Report - HouseholdWasteManagementSystem  (2026-10-25)

## Corpus Check
- 5 recognized files · ~3,964 words
- 3 files lack native extraction: `.gitignore`, `.graphifyignore`, and `style.css`. The stylesheet is represented by a source-backed file node, but its CSS rules are not parsed.

## Summary
- 48 nodes · 54 edges · 8 communities (5 shown, 3 thin omitted)
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.95)
- Token cost: 0 input · 0 output

## Refresh Notes
- `refresh_project_links.py` verifies three README/HTML feature correspondences and source-backed links for the page script, stylesheet, browser storage, Google Fonts, and live GitHub Pages URL. The three section-to-summary links remain marked as inferred.
- The graph has 54 links; Graphify HTML renders 54 edges with no duplicate endpoint pairs or dangling nodes.
- The ≤1-connection warning includes intentional boundary endpoints, the file-level `observeRevealTargets()` helper, and project guidance concepts; no speculative edges were added.

## Graph Freshness
- Built from commit: `ac922052`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Household Rules and Rollout
- Site Content and Assets
- GitHub Actions Triggers
- Jekyll Build Steps
- Project Instructions
- Archify Diagram Guidance
- Graphify Index Guidance
- Client Interactions and Browser Storage

## God Nodes (most connected - your core abstractions)
1. `Home waste management presentation page` - 11 edges
2. `Household Waste Management System README` - 7 edges
3. `Five-stream household sorting plan` - 5 edges
4. `steps` - 4 edges
5. `Project instructions` - 4 edges
6. `updateProgress()` - 3 edges
7. `build` - 3 edges
8. `Household compliance checklist, fines, and rewards` - 3 edges
9. `Adapt German waste streams to Thai infrastructure and climate` - 3 edges
10. `Separate outbound routes for recyclables, organics, residual, and hazardous waste` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Home waste management presentation page` --implements--> `showPanel()`  [EXTRACTED]
  index.html → app.js
- `Household compliance checklist, fines, and rewards` --implements--> `updateProgress()`  [EXTRACTED]
  index.html → app.js
- `Household Waste Management System README` --references--> `updateProgress()`  [EXTRACTED]
  README.md → app.js
- `Household compliance checklist, fines, and rewards` --implements--> `Household sorting penalties and rewards`  [INFERRED]
  index.html → README.md
- `Four-week implementation roadmap and maintenance schedule` --implements--> `Four-week household rollout and maintenance plan`  [INFERRED]
  index.html → README.md

## Import Cycles
- None detected.

## Communities (8 total, 3 thin omitted)

### Community 0 - "Household Rules and Rollout"
Cohesion: 0.25
Nodes (9): updateProgress(), GitHub Pages live site, Household compliance checklist, fines, and rewards, Four-week implementation roadmap and maintenance schedule, Printable Thai bin labels and collection-day bag tags, Printable bilingual Thai waste labels and bag tags, Four-week household rollout and maintenance plan, Household sorting penalties and rewards (+1 more)

### Community 1 - "Site Content and Assets"
Cohesion: 0.23
Nodes (10): Google Fonts, Bokashi composting guide and comparison with alternatives, Five color-coded waste streams and accepted items, German-to-Thai waste stream mapping, Home waste management presentation page, Bokashi processing for household organic waste, Five-stream household sorting plan, Saleng and recycling-service outbound routes (+2 more)

### Community 2 - "GitHub Actions Triggers"
Cohesion: 0.25
Nodes (7): jobs, name, branches, branches, True, pull_request, push

### Community 3 - "Jekyll Build Steps"
Cohesion: 0.33
Nodes (6): runs-on, steps, build, name, run, uses

### Community 4 - "Project Instructions"
Cohesion: 0.40
Nodes (4): Project AGENTS Standard, Project data, Project instructions, Workspace Add-on Inventory

## Knowledge Gaps
- **10 low-degree node(s):** `Browser localStorage checklist state`, `GitHub Pages live site`, `Google Fonts`, `Project AGENTS Standard`, `Workspace Add-on Inventory` (+5 more)
  These have ≤1 connection. This includes intentional external-service and browser-state endpoints, so the count alone does not imply missing relationships. (20 nodes total have ≤1 connection when file, concept, and rationale nodes are included.)
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore them.

## Suggested Questions
_Questions this graph can help answer:_

- **How does the page load its client behavior and stylesheet?**
  Follow the source-backed page links to `app.js` and `style.css`.
- **Where does checklist state persist?**
  `app.js` reads and writes the browser's `localStorage`.
- **Which household guidance appears both in the site and the README?**
  Follow the three explicitly marked inferred feature-summary links and compare their cited sections.
