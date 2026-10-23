# Graph Report - HouseholdWasteManagementSystem  (2026-10-24)

## Corpus Check
- Corpus is ~3,876 words - fits in a single context window. You may not need a graph.

## Summary
- 35 nodes · 40 edges · 5 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: unavailable (agent usage metadata was not exposed)

## Community Hubs (Navigation)
- Page Interaction and Checklist
- GitHub Pages Workflow
- Implementation and Materials
- Deployment Steps
- Waste Sorting System

## God Nodes (most connected - your core abstractions)
1. `Home waste management presentation page` - 8 edges
2. `Household Waste Management System README` - 6 edges
3. `Five-stream household sorting plan` - 5 edges
4. `steps` - 4 edges
5. `build` - 3 edges
6. `updateProgress()` - 3 edges
7. `Adapt German waste streams to Thai infrastructure and climate` - 3 edges
8. `push` - 2 edges
9. `pull_request` - 2 edges
10. `jobs` - 2 edges

## Surprising Connections (you probably didn't know these)
- `Home waste management presentation page` --implements--> `showPanel()`  [EXTRACTED]
  index.html → app.js
- `Household compliance checklist, fines, and rewards` --implements--> `updateProgress()`  [EXTRACTED]
  index.html → app.js
- `Household Waste Management System README` --references--> `updateProgress()`  [EXTRACTED]
  README.md → app.js
- `Five color-coded waste streams and accepted items` --implements--> `Five-stream household sorting plan`  [EXTRACTED]
  index.html → README.md
- `German-to-Thai waste stream mapping` --implements--> `Adapt German waste streams to Thai infrastructure and climate`  [EXTRACTED]
  index.html → README.md

## Import Cycles
- None detected.

## Communities (5 total, 0 thin omitted)

### Community 0 - "Page Interaction and Checklist"
Cohesion: 0.29
Nodes (6): showPanel(), updateProgress(), Household compliance checklist, fines, and rewards, Four-week household rollout and maintenance plan, Household sorting penalties and rewards, Household Waste Management System README

### Community 1 - "GitHub Pages Workflow"
Cohesion: 0.25
Nodes (7): jobs, name, branches, branches, True, pull_request, push

### Community 2 - "Implementation and Materials"
Cohesion: 0.29
Nodes (8): Bokashi composting guide and comparison with alternatives, Four-week implementation roadmap and maintenance schedule, German-to-Thai waste stream mapping, Home waste management presentation page, Printable Thai bin labels and collection-day bag tags, Printable bilingual Thai waste labels and bag tags, Bokashi processing for household organic waste, Adapt German waste streams to Thai infrastructure and climate

### Community 3 - "Deployment Steps"
Cohesion: 0.33
Nodes (6): runs-on, steps, build, name, run, uses

### Community 4 - "Waste Sorting System"
Cohesion: 0.40
Nodes (3): Five color-coded waste streams and accepted items, Five-stream household sorting plan, Saleng and recycling-service outbound routes

## Knowledge Gaps
- **4 isolated node(s):** `Saleng and recycling-service outbound routes`, `Household sorting penalties and rewards`, `Four-week household rollout and maintenance plan`, `Four-week implementation roadmap and maintenance schedule`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 12 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Home waste management presentation page` connect `Implementation and Materials` to `Page Interaction and Checklist`, `Waste Sorting System`?**
  _High betweenness centrality (0.138) - this node is a cross-community bridge._
- **What connects `Saleng and recycling-service outbound routes`, `Household sorting penalties and rewards`, `Four-week household rollout and maintenance plan` to the rest of the system?**
  _4 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Why does `Household Waste Management System README` connect `Page Interaction and Checklist` to `Implementation and Materials`, `Waste Sorting System`?**
  _High betweenness centrality (0.117) - this node is a cross-community bridge._
- **Why does `Five-stream household sorting plan` connect `Waste Sorting System` to `Page Interaction and Checklist`, `Implementation and Materials`?**
  _High betweenness centrality (0.102) - this node is a cross-community bridge._