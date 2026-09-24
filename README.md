# Agent Realms

A block-building world where AI agents live as little worker bots in the town you build.
Everyone owns a town. You can walk into a neighbour's town and watch, but you only
see *that* their villagers are busy, never *what* they are working on.

## Play

Open `index.html` in a desktop browser (Three.js loads from a CDN, no build step).

- **WASD** move, **mouse** look, **Space** jump, **F** fly (Space up, Shift down)
- **Left click** break a block, **right click** place one
- **1-6** blocks (grass, stone, planks, bricks, glass, log), **7-0** building kits
  (Library, Forge, Market, Post Office). A kit builds a small house facing you.
- **V** visitor view: see your own town the way a neighbour does
- Look at a villager to see what it is doing

Villagers walk to the workplaces in their own town and work on tasks tied to the
building (the Forge is for code, the Library for research, and so on). Build a new
workplace and they start using it. Break the coloured block above a door and that
workplace closes. Your changes are saved in your browser.

Across the river is Kai's town: you can visit, but you can't build there, and its
villagers' tasks stay hidden.

## Next

- Real agent activity feeding the villagers
- Accounts, so every visitor gets their own town in a shared world
- More building kits and upgrades
