# HexIt: hexahedral block decomposition by expert iteration

Project page and (soon) code for **Learning Hexahedral Block Decompositions of Polyhedra with Expert Iteration on
Combinatorial Maps**.

<p align="center"><img src="docs/media/solid-to-mesh.png" width="720" alt="A large chamfered solid, the 56 hexahedra the agent splits it into, and the same mesh as a wireframe"></p>

An agent that splits a 3D solid into hexahedral blocks one insert at a time (a vertex, an edge or a face), cloned from
decompositions that can be written down and then improved by expert iteration: it keeps its own successful
decompositions in a growing archive and retrains on them.

The code, trained models and evaluation sets will be released here together with the paper.

## Project page

`docs/` is the project page, served by GitHub Pages (Settings → Pages → deploy from branch `main`, folder `/docs`).
The gallery clips are in `docs/media/gallery/`.
