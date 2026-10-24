# Graph Report - HouseholdWasteManagementSystem  (2026-10-25)

## Corpus Check
- 5 recognized files · ~3,964 words
- Unclassified: 3 files not represented in the graph: `.gitignore`, `.graphifyignore`, and `style.css`.

## Summary
- 47 nodes · 52 edges · 9 communities (6 shown, 3 thin omitted)
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.95)
- Token cost: 0 input · 0 output

## Refresh Notes
- `refresh_project_links.py` verifies three README/HTML feature correspondences and adds source-checked links for localStorage, Google Fonts, and the published GitHub Pages URL. The three section-to-summary links remain marked as inferred.
- The graph has 52 links; Graphify HTML renders 52 edges with no duplicate endpoint pairs or dangling nodes.

## Graph Freshness
- Built from commit: `ac922052`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Page Interaction and Checklist
- Organic Processing and Thailand Adaptation
- GitHub Actions Triggers
- Jekyll Build Steps
- Project Instructions
- Archify Diagram Guidance
- Graphify Index Guidance
- Site Content and External Resources
- Waste Stream Planning and Routes

## God Nodes (most connected - your core abstractions)
1. `Home waste management presentation page` - 9 edges
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
- `Five color-coded waste streams and accepted items` --implements--> `Five-stream household sorting plan`  [EXTRACTED]
  index.html → README.md
- `Household compliance checklist, fines, and rewards` --implements--> `Household sorting penalties and rewards`  [INFERRED]
  index.html → README.md

## Import Cycles
- None detected.

## Communities (9 total, 3 thin omitted)

### Community 0 - "Page Interaction and Checklist"
Cohesion: 0.22
Nodes (9): showPanel(), updateProgress(), Browser localStorage checklist state, GitHub Pages live site, Household compliance checklist, fines, and rewards, Four-week implementation roadmap and maintenance schedule, Four-week household rollout and maintenance plan, Household sorting penalties and rewards (+1 more)

### Community 1 - "Organic Processing and Thailand Adaptation"
Cohesion: 0.50
Nodes (4): Bokashi composting guide and comparison with alternatives, German-to-Thai waste stream mapping, Bokashi processing for household organic waste, Adapt German waste streams to Thai infrastructure and climate

### Community 2 - "GitHub Actions Triggers"
Cohesion: 0.25
Nodes (7): jobs, name, branches, branches, True, pull_request, push

### Community 3 - "Jekyll Build Steps"
Cohesion: 0.33
Nodes (6): runs-on, steps, build, name, run, uses

### Community 4 - "Project Instructions"
Cohesion: 0.40
Nodes (4): Project AGENTS Standard, Project data, Project instructions, Workspace Add-on Inventory

### Community 7 - "Site Content and External Resources"
Cohesion: 0.40
Nodes (5): Google Fonts, Five color-coded waste streams and accepted items, Home waste management presentation page, Printable Thai bin labels and collection-day bag tags, Printable bilingual Thai waste labels and bag tags

## Knowledge Gaps
- **9 isolated node(s):** `Project AGENTS Standard`, `Workspace Add-on Inventory`, `Archify Diagrams`, `Workspace Archify Guidance`, `Graphify Persistent Index` (+4 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 19 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Home waste management presentation page` connect `Home waste management presentation page` to `Page Interaction and Checklist`, `Adapt German waste streams to Thai infrastructure and climate`, `Five-stream household sorting plan`?**
  _High betweenness centrality (0.107) - this node is a cross-community bridge._
- **What connects `Project AGENTS Standard`, `Workspace Add-on Inventory`, `Archify Diagrams` to the rest of the system?**
  _9 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Why does `Household Waste Management System README` connect `Page Interaction and Checklist` to `Five-stream household sorting plan`, `Home waste management presentation page`?**
  _High betweenness centrality (0.080) - this node is a cross-community bridge._
- **Why does `Five-stream household sorting plan` connect `Five-stream household sorting plan` to `Page Interaction and Checklist`, `Adapt German waste streams to Thai infrastructure and climate`, `Home waste management presentation page`?**
  _High betweenness centrality (0.051) - this node is a cross-community bridge._