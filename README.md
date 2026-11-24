# 4D Polytope Viewer

A stereoscopic viewer for four-dimensional polytopes, in a single
self-contained HTML file (`polytope.html`). No build step or dependencies:
open it in a browser.

The canvas shows two images side by side. Cross your eyes until they merge
into one central image to see the 3D projection in depth.

## Polytopes

- The six convex regular 4-polytopes: 5-cell, tesseract (8-cell), 16-cell,
  24-cell, 600-cell, 120-cell
- Uniform polytopes: bitruncated 24-cell (48-cell), snub 24-cell,
  omnitruncated 5-cell
- The disphenoidal 288-cell
- Root polytopes: A4, B4/C4, and the 240 E8 roots projected to 4D

The omnitruncated 5-cell is the permutohedron of order 5: its vertices are
the 120 rankings of five candidates, placed at their Borda score vectors,
and its edges swap two adjacent candidates, so path length is the Kendall
tau distance.

## Features

- Continuous 4D rotation in all six coordinate planes, with adjustable and
  optionally drifting speeds
- Perspective or orthographic projection, stereographic 3-sphere view, and a
  3D-hyperplane projection mode
- Decompositions into inscribed polytopes (e.g. 24-cell triality, the 25
  24-cells of the 600-cell, the 5 600-cells of the 120-cell, rankings
  grouped by winner or loser)
- Cell highlighting for the 5-, 8-, 16-, 24-cell and omnitruncated 5-cell
- Lattice view of the tilings of 4D by tesseracts, 16-cells and 24-cells
- Coloring by w coordinate or hexachromatic (one color angle per eye),
  vertex trails, 4D coordinate axes

## Controls

- Drag in the left half to rotate in XY/XZ, in the right half for YZ/YW;
  hold Shift for XZ/XW and YW/ZW
- Mouse wheel zooms
- Fullscreen (F, or double-click the picture) shows only the two images;
  F, Esc or a double-click leaves it

Keyboard shortcuts (also shown on the buttons):

| Key | Action | Key | Action |
|---|---|---|---|
| Space | pause / resume | R | reset rotation |
| F | fullscreen | ← → | previous / next polytope |
| D | next decomposition | C | cell highlighting |
| P | 3D projection | A | axes |
| H | hexachromatic | G | gradients |
| L | lattice | T | trails |
| M | speed mutation | O | orthographic |
| S | 3-sphere view | | |

## License

Licensed under the GNU General Public License, version 3 or (at your
option) any later version. See [LICENSE](LICENSE) for the full text.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
or FITNESS FOR A PARTICULAR PURPOSE.
