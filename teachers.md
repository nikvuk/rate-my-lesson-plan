# Getting started - for teachers

## Intro

By the end of this, your students will have built a system that allows them
to rate lessons by using physical buttons on a BBC Microbit.

It should take a few hours to run this lesson.

## You will need

* A [BBC Microbit](http://microbit.org/) per group. We recommend each group to have 2-4
students.
* Access to a computer with a web browser for each group.

## Step 1 - Get to the simulator

Direct your students to the online simulator at https://makecode.microbit.org.

The interface they're presented with will look something like this:

![](assets/0.png)

The right hand side of the interface has the visual editor, where students can drag and drop elements of the program and built it up.

The left side is a virtual version of the Microbit. It functions exactly as a real one would, including pressable buttons.

## Step 2 - Code the program

Students can now use the editor to create the program and test it on the simulator. They can choose to use either the _Blocks_ or _JavaScript_ editor (see the toggle at the top of the screen).

The program needs to do the following things:

1. Keep record of a score and display it on the LED panel, beginning at zero.
1. When button A is pressed, decrease the score by one and briefly show an `X` icon on the LED panel.
1. When button B is pressed, increase the score by one and briefly show a `tick` icon on the LED panel.
