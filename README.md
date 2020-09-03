# Coblok -- A collaborative block design task

Coblok is a task for assessing pair performance in virtual reality and reality

## Rules:

All the blocks (cube, sphere, cylinder, pyramid, cone, long cuboid and long cylinder) in two different colours (red and white are recommended for 3D prints, red and yellow for virtual reality) are available to the participants at all times.

Puzzles consist of two cards. Each participant receives one of the puzzle cards for a puzzle. Each card contains a flat projection consisting of two-dimensional shapes of a configuration of three-dimensional blocks. Each 2D shape (circle, square, rectangle and triangle) match several 3D blocks. Flat projections are simplified images, wich do not contain any depth or perspective information: in the puzzle cards the 3D blocks of the final configuration resemble a 2D shape from a certain angle. The shapes in the flat projections are always the same size regardless where the blocks are placed in the depth-axis. The blocks can be occluded both completely and partially by another block being placed in front, but no blocks are completely occluded in both cards for one puzzle. 

The participants task is to figure out, as quickly and accurately as possible, the configuration of blocks that matches both of their puzzle cards. The participants are not allowed to show their cards to each other. Otherwise they are allowed to communicate freely, but without any external tools, such as pen and paper.

## Information

This repository contains all the necessary components for the coblok task.

The components are organized into folders as follows:
    - puzzle_cards: contains the puzzles for two sets of five puzzles and two examples
    - block_cards: contains cards representing each block in the task for aiding the task explanation
    - blocks_3d: contains STL files for all the blocks that can be imported to a 3D engine or 3D printed
    - enclosures: contains PDF files for laser cutting acrylic enclosures for 3D printed blocks (created with [Box Designer](http://boxdesigner.connectionlab.org)).

