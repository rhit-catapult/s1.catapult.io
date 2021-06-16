---
layout: page
title: TicTacToe Game
---

# Table of contents


<!-- vim-markdown-toc GFM -->

* [Introduction](#introduction)
* [Code structure](#code-structure)
  * [1. The helper functions](#1-the-helper-functions)
  * [The `Game` class](#the-game-class)
  * [The `ViewController` class](#the-viewcontroller-class)
* [TODO 1-3: The game loop](#todo-1-3-the-game-loop)
  * [TODO 1](#todo-1)
  * [TODO 2](#todo-2)
  * [TODO 3](#todo-3)

<!-- vim-markdown-toc -->

# Introduction

So far, in raindrops, we have built what might help us in building arcade-style
games. But what if we would like to build a board game? Well, we've got you
covered, we will be building a playable Tic-Tac-Toe game in the module, so let's
go ahead and dive right in!

# Code structure

Our code is split into 4 major pieces: helper functions, the `Game` class, the
`ViewController` class, and the main game loop. Let's talk about the first three
in some detail. The main game loop is pretty much similar to what we have been
doing in the past modules and projects. 

## 1. The helper functions

First, we provide you with two helper functions: `get_row_col` and
`get_xy_position`. A tic-tac-toe game is divided into 9 regions (blocks on the
screen) that contain an 'X' or an '0' or nothing, each. However, `pygame` does
not know about these blocks or regions, all it understands is coordinates. So we
need a way to convert between the regions and the `pygame` positions. 

The function `get_row_col` takes as input an x and a y coordinate, and converts
those to which block or regions of the game board those coordinates correspond. 

On the other hand, the function `get_xy_position` takes as an input a certain
region (represented by a row and col out of the 9 possible regions), and
converts it to its corresponding x and y coordinates on the screen. It is
perfectly okay if you do not understand how these functions work, all what
matters is that you understand what you do at a high-level and then can use them
in your code as you see fit. 

## The `Game` class

This class captures all of the dynamics of the game, meaning the process of
taking turns as well as the process of checking if the game is over. The methods
`take_turn` and `check_for_game_over` do exactly that, respectively. This is
where you will implement the __logic__ of the game. 

## The `ViewController` class

This class captures the _view_ of the game, i.e., what the game looks like at a
specific moment in time, for a specific set of made actions. It is responsible
for drawing the game on the screen as well as handling the events that `pygame`
generates. 

# TODO 1-3: The game loop

Let's go ahead and take care of the game loop. We have provided you with the
initial skeleton for all the classes you need to implement, so we can use them
now and then complete them as we implement the `TODO`s in the code. 

## TODO 1

In this section, we will first instantiate (i.e., create or give birth to) an
instance of the `ViewController` class. This is similar to how we built points
in the `Point class`. Go ahead and try to implement this on your own, then check
the solution below

<details>

```python
# TODO 1: Create an instance of the ViewController class called view_controller
view_controller = ViewController(screen)
```

</details>

## TODO 2

In this section, we need to call the `check_event` method from our created view
controller, and pass it the current `event` as an argument. Try to implement
this yourself, then check the solution below.

<details>

```python
# TODO 2: Pass the event to the view_controller
view_controller.check_event(event)
```

</details>

## TODO 3

In this section, we will draw the view controller that we instantiated (created)
earlier, so let's go ahead and do that, then check the solution below

<details>

```python
# TODO 3: Draw the view_controller
view_controller.draw()
```

</details>
