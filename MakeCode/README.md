# Getting started with MakeCode Arcade

> This repo provides an overview of how to program the PyBadge with [Microsoft MakeCode Arcade](https://arcade.makecode.com/).

![MakeCode Arcade Screenshot](assets\MakeCodeArcade-mylilai_small.png)

This doc gives some general information and guidance on how to get started programming the PyBadge with MakeCode.

## Contents
| Section     | Description                                |
|-------------------|--------------------------------------------|
|[Introduction](##Introduction) | More information about the PyBadge, including what's on the board. |
| [Programming with MakeCode](##Getting-a-MakeCode-program-on-the-PyBadge) | A quick overview on how to program the Pybadge with MakeCode with troubleshooting tips and resources.
| [Suggested Learning Path](##Suggested-Learning-Path) | This section provides a brief curriculum with project-based resources for art, games, and sensors.


## Introduction
Congratulations, you've got yourself a PyBadge! The PyBadge is device called a *microcontroller,* a simple computer that we can program to do all sorts of fun things, like custom video games, music boxes, and more!

We can write instructions, called programs, for the PyBadge using Microsoft MakeCode Arcade which is a block-based coding platform similar to Scratch. Read on to learn more about the board and what you can make with it!

### What's on the board
* Color screen display (1.8" 160x128 Color TFT Display) 
* 8 x Game/Control Buttons 
* Light sensor (on front) 
* Buzzer mini-speaker
* Triple-axis accelerometer (motion sensor)
* 5 x NeoPixels (lights that can change colors!)
* LiPoly battery port (recharging capabilities)
* USB port for battery charging, programming and debugging
* Mono Class-D speaker driver for 4-8 ohm speakers, up to 2 Watts
    * Like [this](https://www.adafruit.com/product/1313) or [this](https://www.adafruit.com/product/4227) speaker!
* Reset button
* On-Off switch

For the full list of features, [visit this site](https://www.adafruit.com/product/4200).

## Getting a MakeCode program on the PyBadge
![MakeCode Arcade: choose hardware screenshot](\assets\Arcade-ChooseHardware1.png)
1. Download the program:
     * In MakeCode Arcade, click "Download" and "Choose Hardware," then select "Adafruit PyBadge" on the top right.
     * The program (a .uf2 file) will save to your computer. Note where it's saved or choose a folder.
     * After this first setup, you can simply click the Download button on the MakeCode Arcade editor page. 

![PyBadge Bootloader mode](\assets\PyBadgeBootMode.jpg)
1. Put the device into bootloader mode: 
    * Double-tap the PyBadge reset button to get it to appear as a device on the computer, much like a USB drive.
    * When the board is in bootloader mode you'll see a screen similar to the above one show up.
    * Now that the board is in bootloader mode, you should see a BADGEBOOT drive show up on your computer. Drag the arcade game .uf2 file onto the drive.
4. Once the file is copied over the board will restart and launch the program!

### General Resources
* [Navigating MakeCode Arcade](https://learn.adafruit.com/how-to-make-games-on-makecode-arcade/navigating-makecode-arcade): an overview of the MakeCode interface 
* [Arcade Game Maker Guide](https://arcade.makecode.com/skillmap): A multi-tutorial guide for learning how to make games in MakeCode Arcade. Includes certificates for completed tutorials.


### Troubleshooting
1. Make sure you're using a data transfer USB cable (one of the most common blockers w/ hardware functioning properly).
1. You may need to update the bootloader on the PyBadge, particularly if you're working on a Mac. If you notice your board is titled "ARCADE-D51" or "BADGEBOOT", [follow this tutorial](https://learn.adafruit.com/adafruit-pybadge/updating-the-bootloader).
2. Troubleshooting help:
    - [Latest Arcade topics - Microsoft MakeCode](https://forum.makecode.com/c/Share-your-Arcade-projects-here/5)
    - [Adafruit customer service forums: MakeCode](https://forums.adafruit.com/viewforum.php?f=64)

## Suggested Learning Path
### Lesson 0: Test Program
> Estimated time: 30 - 45 minutes.

> Recommended ages: All!

This lesson introduces students to MakeCode Arcade and shows them how to load MakeCode programs onto the PyBadge.

1. Start by giving students some time to explore MakeCode Arcade and create a creature or character. 
2. Show students how to download the program and load onto the PyBadge. 
3. Depending on students' experience, include 10 - 15 minutes for loading a first test program. 
4. If students finish early, encourage them to start adding to their test program by making the character move, adding a background, or exploring the on-board sensors.
5. Encourage students to share their creations, what worked well, what was surprising, and any mysteries or questions they have.

### Lesson 1: Open-ended exploration
> Estimated time: 60 - 90 min, longer as needed

> Recommended ages: 8+

Provide students an open-ended prompt and allow them to design and build a solution using MakeCode Arcade and the PyBadge.

It may be helpful to start with a short lesson on the **Design Thinking Process**. [Here's a helpful resource created by the Stanford D School](https://kissingergroup.com/wp-content/uploads/2020/06/An-Introduction-to-Design-Thinking.pdf).

If students are unsure what to make, suggest they write down their values, or things they care about, and use one to motivate a project. 

**Sample prompts**
* Make something for someone you love
* Make something inspired by nature
* Design a solution for an everyday problem
* Invent an instrument
* Design a game (for 2 or more people) 
* Explore other prompts based on students' interests!


### Lessons 2 and onward: Build a project!
> Estimated time: 60 min

> Recommended ages: 8+

#### Art & Games
**Beginner**
* Check out the tutorials in [MakeCode Arcade](https://arcade.makecode.com/)!
* [Pixel Art](https://learn.adafruit.com/makecode-arcade-pixel-art-sprites): A fantastic guide to making pixel art in MakeCode Arcade.
* [Name Badge](https://learn.adafruit.com/making-a-name-tag-in-makecode-arcade/starting-your-name-tag): Make a custom name badge!
* [Sparky Invaders](https://learn.adafruit.com/makecode-arcade-sparky-invaders): Learn how to make a game inspired by Space Invaders!

**Intermediate to Advanced**
* [Making Platform Games](https://learn.adafruit.com/makecode-arcade-platform-level): learn how to make scrolling platformer games like Super Mario Bros for NES!
* [Re-Making Classics: Arkanoid](https://learn.adafruit.com/re-makecode-the-classics-arkanoid): A tutorial showing you the logic and blocks for making the classic Arkanoid game.
* [my lil' ai](https://youtu.be/kNZUletw9lg): A digital pet that teaches the basics of machine learning (ML), or AI. 
* [Adding features to games](https://learn.adafruit.com/next-level-makecode-arcade-games): Learn how to enhance graphics, add background music, and use neopixels to track in-game stats.
* [Adding custom color palettes](https://learn.adafruit.com/custom-color-palettes-for-makecode-arcade-games): Learn how to add custom color palettes to MakeCode Arcade.

#### Sensors and Beyond!
**Beginner**
* [PyBadge Plant Monitor](https://learn.adafruit.com/plantagotchi-pybadge-plant-monitor): Using just the PyBadge (and a plant on-hand), program a plant monitor in MakeCode Arcade.
* [Marble Labyrinth Game](https://learn.adafruit.com/pygamer-marble-labyrinth-in-makecode-arcade): Use the accelerometer to simulate a marble labyrinthe maze game.
* [Digital Sand](https://learn.adafruit.com/pixeldust-digital-sand-demos-for-arcada): Learn how to create motion-activated effects for the PyBadge

**Intermediate to Advanced**
* [Sensors in MakeCode](https://learn.adafruit.com/sensors-in-makecode): Learn how to use sensors in MakeCode! 
    * (Note: this tutorial focuses on the Circuit Playground Express but may be adapted for the PyBadge)

