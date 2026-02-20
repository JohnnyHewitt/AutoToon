# Phase I: Research Tools & Techniques

> Owner: John Hewitt  ·  Created: 2026-02-19

## Begin (raw)
<!-- 3-minute brain dump. Do not edit or reinterpret. -->

Research open-source 2D cartoon creation tools — the kind used for modern cartoons
(Futurama, Bob's Burgers style), not AI frame-by-frame generation. AI will handle
assets, storyboards, and automating processes like animating assets within the chosen
tool, possibly via MCP. Also supporting B/W noir style. Prefer open source for easier
MCP integration. Web-based tool for building/organizing assets.

## Refine (scope)
- **Goal**: Know exactly what tools we'll be using, their cost, and pros/cons. Know how to get assets into the tool. Know how we'll manage storyboards, animation, sound, etc.
- **In scope**: 2D animation tool evaluation, asset pipeline research, storyboard management, animation workflow, sound integration, MCP/API controllability analysis
- **Out of scope**: AI frame-by-frame rendering approaches; actual implementation (that's Phase II)
- **Definition of Done**: Tool selected with clear rationale. Cost breakdown complete. Asset pipeline from AI generation into tool documented. Storyboard, animation, and sound workflows defined. API/scripting capabilities confirmed for future MCP wrapping.
- **Constraints**:
  - Tool must be 100% scriptable or API-controllable (AI will drive it)
  - One-time purchase OK, no recurring costs
  - Open source with source code preferred (for tweaking + MCP integration)
  - Quality over ease of use (automation handles the UX)
- **Risks**: Best tool may not have sufficient API/scripting; may need to combine multiple tools
- **Resources**: TBD during research
- **Dependencies**: None — this is the starting point
