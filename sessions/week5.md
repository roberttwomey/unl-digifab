# Week 4 - Mesh Creation and Stacked Contours

## Agenda
- Announcements:
  - Configure Rhinoceros Zoo (carson center license for Rhino 6.0)
    - (Update: is working on wired connection, still not working on eduroam for me)
- Q&A on Exercise 3. Cutting time.
- Topics
  - Recap from [last week](sessions/week3.md)
    - new: Fabricating 3D Form from 2D Materials with Laser Cutter ([slides](https://docs.google.com/presentation/d/1ARPiH8T5reSiY5ewIX1UlxRUFG-ZnqqxFOQk_W-92V0/edit?usp=sharing))
  - [Mesh Basics in Rhino](#mesh-basics-in-rhino)
  - [Contours and Stacked Construction](#contours-and-stacked-construction)
  - [Bonus: Pepakura and Unfolding](#bonus-pepakura-and-unfolding)
- [Homework](#homework)
- [Office Hours this Week](#office-hours)

# Mesh Basics in Rhino
- Solids
  - what are they? (collections of surfaces)
  - explode, cap
  - when we export STL we are creating a mesh
- Meshes
  - create meshes directly
  - importing
    - [buffalo.3dm](../assets/day4/buffalo.3dm)
  - simplification (reduce), edit
- [solids_meshes.3dm](../assets/day4/solids_meshes.3dm)

# Contours and Stacked Construction
- Building a 3d form directly with stacks of contours
  - freeform drawing
  - offset
  - extrude to priview (optional)
  - [stacked_contours_offset.3dm](../assets/day4/stacked_contours_offset.3dm)
- Slicing a 3d mesh or surface object into 2d stacks
  - the [contour](http://docs.mcneel.com/rhino/5/help/en-us/commands/contour.htm) command
  - [contour_command.3dm](../assets/day4/contour_command.3dm)
  - [contour_flatten_shear.3dm](../assets/day4/contour_flatten_shear.3dm)
- Importing and slicing a complex mesh
  - Finding a mesh (thingiverse.com)
  - Importing a mesh into rhino
  - Slicing a mesh with the contour command
  - slicing/design for digital fabrication (material thickness considerations)
    - [buffalo_contours.3dm](../assets/day4/buffalo_contours.3dm)
    - [sliced_pikachu.3dm](../assets/day4/sliced_pikachu.3dm)
  - sliced pikachu

# BONUS: Pepakura and Unfolding
- Unfold. more on this later.

# Homework
- Exercise 4 DUE Thursday September 23, 9pm
- Concept for project 1. 2 paragraphs on Canvas.

# Office Hours
- Tuesday afternoon 9/21 
- Wednesday afternoon 9/22 (after 1pm)

# Reference