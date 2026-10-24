# Graph Report - HouseholdWasteManagementSystem  (2026-10-25)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 54 nodes · 58 edges · 8 communities (6 shown, 2 thin omitted)
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 4 edges (avg confidence: 0.95)
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
- CLAUDE.md

## God Nodes (most connected - your core abstractions)
1. `Home waste management presentation page` - 8 edges
2. `HouseholdWasteManagementSystem Graphify Instructions` - 7 edges
3. `Household Waste Management System README` - 6 edges
4. `Five-stream household sorting plan` - 5 edges
5. `steps` - 4 edges
6. `Project instructions` - 4 edges
7. `updateProgress()` - 3 edges
8. `build` - 3 edges
9. `Adapt German waste streams to Thai infrastructure and climate` - 3 edges
10. `Separate outbound routes for recyclables, organics, residual, and hazardous waste` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Home waste management presentation page` --implements--> `showPanel()`  [EXTRACTED]
  index.html → app.js
- `Household compliance checklist, fines, and rewards` --implements--> `updateProgress()`  [EXTRACTED]
  index.html → app.js
- `Household Waste Management System README` --references--> `updateProgress()`  [EXTRACTED]
  README.md → app.js
- `Graphify Persistent Index` --semantically_similar_to--> `Graphify Knowledge Graph`  [INFERRED] [semantically similar]
  AGENTS.md → CLAUDE.md
- `Four-week implementation roadmap and maintenance schedule` --implements--> `Four-week household rollout and maintenance plan`  [INFERRED]
  index.html → README.md

## Import Cycles
- None detected.

## Communities (8 total, 2 thin omitted)

### Community 0 - "Page Interaction and Checklist"
Cohesion: 0.29
Nodes (8): Bokashi composting guide and comparison with alternatives, Five color-coded waste streams and accepted items, German-to-Thai waste stream mapping, Home waste management presentation page, Bokashi processing for household organic waste, Five-stream household sorting plan, Saleng and recycling-service outbound routes, Adapt German waste streams to Thai infrastructure and climate

### Community 1 - "GitHub Pages Workflow"
Cohesion: 0.20
Nodes (10): Graphify Persistent Index, Workspace Graphify Guidance, graphify explain Command, HouseholdWasteManagementSystem Graphify Instructions, Graphify Knowledge Graph, graphify path Command, graphify query Command, Graphify Architecture Report (+2 more)

### Community 2 - "Implementation and Materials"
Cohesion: 0.22
Nodes (9): showPanel(), updateProgress(), Household compliance checklist, fines, and rewards, Four-week implementation roadmap and maintenance schedule, Printable Thai bin labels and collection-day bag tags, Printable bilingual Thai waste labels and bag tags, Four-week household rollout and maintenance plan, Household sorting penalties and rewards (+1 more)

### Community 3 - "Deployment Steps"
Cohesion: 0.25
Nodes (7): jobs, name, branches, branches, True, pull_request, push

### Community 4 - "Waste Sorting System"
Cohesion: 0.33
Nodes (6): runs-on, steps, build, name, run, uses

### Community 5 - "Project instructions"
Cohesion: 0.40
Nodes (4): Project AGENTS Standard, Project data, Project instructions, Workspace Add-on Inventory

## Knowledge Gaps
- **11 isolated node(s):** `Workspace Graphify Guidance`, `graphify explain Command`, `graphify path Command`, `graphify query Command`, `graphify update Command` (+6 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 23 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Home waste management presentation page` connect `Page Interaction and Checklist` to `Implementation and Materials`?**
  _High betweenness centrality (0.060) - this node is a cross-community bridge._
- **What connects `Workspace Graphify Guidance`, `graphify explain Command`, `graphify path Command` to the rest of the system?**
  _11 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Why does `Household Waste Management System README` connect `Implementation and Materials` to `Page Interaction and Checklist`?**
  _High betweenness centrality (0.037) - this node is a cross-community bridge._
- **Why does `build` connect `Waste Sorting System` to `Deployment Steps`?**
  _High betweenness centrality (0.032) - this node is a cross-community bridge._