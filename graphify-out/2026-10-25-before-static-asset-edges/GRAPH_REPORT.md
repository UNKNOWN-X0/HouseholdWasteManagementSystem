# Graph Report - HouseholdWasteManagementSystem  (2026-10-25)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 44 nodes · 49 edges · 7 communities (5 shown, 2 thin omitted)
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.95)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `ac922052`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Page Interaction and Checklist
- GitHub Pages Workflow
- Implementation and Materials
- Deployment Steps
- Waste Sorting System
- Project instructions
- Archify Diagrams

## God Nodes (most connected - your core abstractions)
1. `Home waste management presentation page` - 8 edges
2. `Household Waste Management System README` - 6 edges
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

## Communities (7 total, 2 thin omitted)

### Community 0 - "Page Interaction and Checklist"
Cohesion: 0.22
Nodes (9): showPanel(), updateProgress(), Household compliance checklist, fines, and rewards, Four-week implementation roadmap and maintenance schedule, Printable Thai bin labels and collection-day bag tags, Printable bilingual Thai waste labels and bag tags, Four-week household rollout and maintenance plan, Household sorting penalties and rewards (+1 more)

### Community 1 - "GitHub Pages Workflow"
Cohesion: 0.29
Nodes (8): Bokashi composting guide and comparison with alternatives, Five color-coded waste streams and accepted items, German-to-Thai waste stream mapping, Home waste management presentation page, Bokashi processing for household organic waste, Five-stream household sorting plan, Saleng and recycling-service outbound routes, Adapt German waste streams to Thai infrastructure and climate

### Community 2 - "Implementation and Materials"
Cohesion: 0.29
Nodes (6): name, branches, branches, True, pull_request, push

### Community 3 - "Deployment Steps"
Cohesion: 0.29
Nodes (7): runs-on, steps, jobs, build, name, run, uses

### Community 4 - "Waste Sorting System"
Cohesion: 0.40
Nodes (4): Project AGENTS Standard, Project data, Project instructions, Workspace Add-on Inventory

## Knowledge Gaps
- **6 isolated node(s):** `Project AGENTS Standard`, `Workspace Add-on Inventory`, `Archify Diagrams`, `Workspace Archify Guidance`, `Graphify Persistent Index` (+1 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 16 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Home waste management presentation page` connect `GitHub Pages Workflow` to `Page Interaction and Checklist`?**
  _High betweenness centrality (0.092) - this node is a cross-community bridge._
- **What connects `Project AGENTS Standard`, `Workspace Add-on Inventory`, `Archify Diagrams` to the rest of the system?**
  _6 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Why does `Household Waste Management System README` connect `Page Interaction and Checklist` to `GitHub Pages Workflow`?**
  _High betweenness centrality (0.057) - this node is a cross-community bridge._