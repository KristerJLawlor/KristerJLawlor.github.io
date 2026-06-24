---
title: 'Empyrean Devlog #1 — Project Kickoff'
description: 'Starting development on Empyrean, a Fire Emblem and Tactics-inspired strategy game built in Unity.'
pubDate: 2026-06-16
project: 'empyrean'
---

## What Is Empyrean?

Empyrean is a tactics RPG I'm building in Unity, inspired by Fire Emblem and other turn-based strategy games. The core loop I'm aiming for: grid-based movement, unit classes with distinct roles, and turn-based combat with terrain and positioning mattering.

## Where I'm Starting

The first milestone is getting a working grid system with units that can move and attack. Before writing any gameplay code I need:

- A tile-based grid that renders correctly and handles coordinate math
- Units that can be placed on the grid and selected
- A turn manager that alternates between player and enemy phases

## First Steps

This week I set up the Unity project and got a basic grid rendering in the scene. Each cell is a prefab with a position calculated from its grid coordinates. Selection highlighting is working — clicking a unit shows its movement range.

Next up is implementing the actual movement — pathfinding within the movement range and animating the unit along the path.

## Follow Along

I'll be posting devlogs here as the project progresses. Check the [Empyrean project page](/projects/empyrean/) for the full overview.
