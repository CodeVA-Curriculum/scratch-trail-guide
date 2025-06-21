---
title: Dino Game
difficulty: 3
video: TODO
description: Learn how to make a version of the Google "No Internet Dino Game" with Scratch! You'll learn all about sprites, dealing with movement controls, handling collisions between sprites, and keeping track of a score.
nodes:
	basic:
		- applications/getting-started.md
		- concepts/sprite-basics.md
		- concepts/looks-blocks.md
		- applications/add-images.md {optional}
		- ./dino-sprites
	movement:
		- $basic
		- ./dino-movement-goals.md
		- concepts/event-blocks.md
		- concepts/motion-blocks.md
		- concepts/control-blocks.md
		- concepts/operator-blocks.md
		- concepts/sensing-blocks.md
		- applications/player-controls.md
		- ./dino-movement
	collisions:
		- $movement
		- ./sensing-dino-collisions.md
		- concepts/variable-blocks.md
		- ./dino-score.md
		- applications/high-score.md {optional}
		- ./dino-prompt.md
---
