# Escape the Grid: A Text-Based Adventure with Walls

In this exercise, you'll write a program that returns all anagrams of a given word. 

## What is a text-based adventure?

A text-based adventure is a game where the player interacts with the game world through text. The player is presented with a description of their surroundings and can type commands to interact with the world. For example, the player might type "go north" to move to a different location, or "take treasure" to pick up an item.

## Setting up your project

It's up to you to decide what type of application to build. You might opt for a simple console/terminal application. Or perhaps you're more comfortable building a web application. You can use any programming language you're comfortable with.

## Exercise 1: Parse the maps

First, let's load the map from a file. You will find an example [file here][1]. The map is a grid of rooms, where each room is represented by a character. The characters have the following meanings:

- `S`: The starting room. You start here.
- `E`: The exit room. You win when you reach this room.
- `X`: A wall. You can't move through walls.
- `T`: A room with a treasure. You can pick up the treasure by moving to this room.
- `.`: An empty room. You can move through empty rooms.

Example map:

```txt
SXT.
...E
XXTX
```

Can you create a program that reads the map from a file and turns it into a data structure that you can use to build the game world? Your world should be a grid of rooms, with each room containing information about its type (e.g. wall, empty, treasure) and the directions you can move in.

## Exercise 2: Move through the map

When the game starts, you start in the room marked with a `S`. Your goal is to reach the room marked with a `E`. You can move in four directions: north, south, east and west. You can only move to rooms that are not blocked by walls. To move, you type the direction you want to move in. For example, if you want to move north, you type `go north`. When you reach the exit, you win!

[1]: ./map.txt
