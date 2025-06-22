---
title: Make a Funny Music Project
description: Make a funny music project with Scratch where you use keystrokes or a sequence to let the user play a beat! When the project plays a sound, it changes the backdrop to show a different silly picture.
video: https://www.youtube.com/watch?v=B7SkUPy5w80
difficulty: 1
icon: 
nodes:
    basic:
        - applications/getting-started.md
        - concepts/sound-blocks.md
        - concepts/event-blocks.md
        - concepts/looks-blocks.md
        - applications/adding-images.md {optional}
        - applications/bitmap-tools.md {optional}
        - applications/vector-tools.md {optional}
        - ./beatbox-program.md
    sequence:
        - $basic
        - concepts/control-blocks.md
        - ./backdrop-timing.md
    sounds:
        - $basic
        - concepts/custom-blocks.md
        - ./custom-sound-trigger-blocks.md
---

In this project, you'll create a silly music project that plays beats and changes the backdrop with each sound. The result is a program where the user can play some music and watch the images change with each sound. The result is usually pretty funny. This is a beginner project--you don't need to know anything about Scratch to get started.

The project goes something like this:

1. First, you'll create the basic program using keystroke input events. Make the program play a sound and change the backdrop to a specific image each time the user presses a key.
2. Next, you can arrange the sounds and backdrop changes in a loop so Scratch plays a beat instead of having the user press the keys. You can even include both of these elements together at the same time so the user can play along with the sequence!
3. Finally (if you want to), you can create custom blocks for each of your sounds, allowing you to create more complicated sequences without repeating as much of your code.