# block-buster
Game

Objective: To match colours between fixed blocks and the placed block to break all connecting blocks of that colour. More blocks broken at once means more points. Get as many points as possible. 

Steps: 
- 4 entances on each side of the grid with 4 options for 2x2 blocks
- 2 different colours possible (this may change) on a 2x2 block
- Pick a 2x2 block and guide it through the grid to a spot
- Place on that spot and matched colours are eliminated
- Game ends when no blocks can move onto the grid

Implementation: 
- React should be sufficient for this, as it's just a grid
- DFS/BFS required for finding all matching colours
- Board contains 1x1 block components, with props passed down to set the colour and a state in the board keeping track of all the colours
