---
title: Guide to Engineering
description: Powering the Colony 101
published: true
date: 2024-08-13T10:03:16.440Z
tags: guide, engineering
editor: markdown
dateCreated: 2024-08-13T09:16:35.670Z
---

> We're still working on this!{.is-warning}

So, you've decided to sign up with the Guild and embark on a journey to become the best damn engineer the galaxy has seen! …or perhaps you're just desperate for power and there's no qualified personnel around. Fret not, this guide will get you sorted either way!

# Introduction to Engineering

![](/diagrams_maps_etc/engineeringlayout.png){.align-center}

<center>Familiarize yourself with the layout of your workplace.</center>

# Generating Power

The primary responsibility of any respectable engineer: Ensuring the colony lights stay on. There are a few options for generating power available to you, and it is up to you which option(s) you go with.

## The Antimatter Engine
![](/ingame_screenshots/antimattersetup/amestep1.png)

This is the Antimatter Engine Bay.

![](/ingame_screenshots/antimattersetup/amestep2.png)

Grab the control console and wrench it down on the wiring knot.

![](/ingame_screenshots/antimattersetup/amestep3.png)

Locate the Antimatter Engine Segments

![](/ingame_screenshots/antimattersetup/amestep4.png)

Set them up in a 3x3 grid like so

![](/ingame_screenshots/antimattersetup/amestep5.png)

Use a multitool on the segment directly adjacent to the console to begin deploying the Antimatter Engine segments

![](/ingame_screenshots/antimattersetup/amestep6.png)

Do the rest of them. Note that the segments will only remain successfully deployed if they are adjacent to an already deployed on.

![](/ingame_screenshots/antimattersetup/amestep7.png)

Locate the antimatter fuel jars (Bright blue bottle to the top left corner of the room), insert it into the console, and power on the unit.

## The Hydroelectric Dam

![](/ingame_screenshots/hydrodam1.png)

This is the Hydroelectric Dam control room. The control console is the only thing you need to interact with.

![](/ingame_screenshots/hydrodam2.png)

The very first thing you must do is hit the Detect Connected Turbines button to link them up with the console.

![](/ingame_screenshots/hydrodam3.png)

Afterwards, simply open the floodgates and you will begin generating power.

## The Diesel Generators

![](/ingame_screenshots/generator1.png)

This is the diesel generator array. They start unfueled.

![](/ingame_screenshots/generator2.png)

Simply grab a fuel tank from the storage area and locate a bucket to fill up the generators, and turn them on.

![](/ingame_screenshots/generator3.png)

You may need more than one tank to fuel all the generators. It's safe to run the generators up to output level 4. At level 5, the generator temperature will exceed 300 degrees celcius and begin overheating. Overheating for a minute straight will result in a sizeable explosion.

# The Substation Setup (and RCON)

So, you're generating lots of energy now, but that power still isn't being fed to the rest of the colony. That's because there are a multitude of power substations located around the colony that takes the raw power output from the main grid and outputs it at a more reasonable level to power the APCs. These substations are not configured to feed from the main grid by default and will quickly drain their energy.

![](/ingame_screenshots/rcon1.png)

The RCON interface, accessed from either a console, tablet, or laptop. The SMES room will have consoles with the RCON software pre-installed. Note that if all else fails, you can physically locate the substations and tweak their settings by hand instead of using the RCON software.

## Setting Substations up Through RCON

![](/ingame_screenshots/rcon2.png)

Simply enable the input, and ensure that the input is always higher than the output.

![](/ingame_screenshots/rconbreaker.png)

Do not flip these bypass breakers unless you really need to. Doing so will directly shunt the main grid's full power into their respective areas, which can result in people losing limbs from tripping over exposed wires and such.