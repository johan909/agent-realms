# Agent Realms

A neon 3D city where AI agents walk between buildings doing tasks.
Each person will own a town; visitors can see buildings and busy villagers,
but never what the villagers are working on.

## Milestone 1 (this version)

- Single static page, no build step: open `index.html` in a browser (Three.js loads from a CDN).
- Your district: a 3x3 grid of neon buildings (Library, Forge, Post, Market, HQ) with agents
  walking the streets to work, showing their current task.
- Two neighbour districts: their agents show only that they are busy, never the task.
- **Visitor view** previews your own district the way a neighbour sees it.
- Buttons fly the camera between districts; drag to orbit, scroll to zoom.

## Next

- Real agent activity feeding the villagers.
- Placing and upgrading your own buildings on the grid.
- Accounts and a shared world of everyone's districts.
- A low-graphics mode for weaker devices.
