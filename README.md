<!-----



Conversion time: 0.819 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β35
* Mon Dec 04 2023 18:44:22 GMT-0800 (PST)
* Source doc: Ball Mania Design Document

WARNING:
You have 4 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->


# Ball Mania


## Game Design


## December 5th 2023




# Table Of Contents


[TOC]





# Introduction

This document specifies a design for the gameplay of a game with the provisional title “Ball Mania”


# Specification


## Concept

The aim of “Ball Mania” is to produce a fun, exciting fast paced multiplayer/family game which involves minigames in a low poly graphics style


## Story


### Setting

The game is set in a low poly cartoon world


## Game Structure

There will be many different minigames which will be played in succession, earning the players tokens, the player with the most tokens will win, tokens are awarded more to players who do better in the chosen minigames. Each minigame will have its own win condition and structure


## Players

Players will be able to split screen on a single standalone machine or play online across a network with many player up to 12


## Action

Players will be able to roll around and smash into other players, causing a bounce effect to occur and both players involved in a collision will be launched the opposite direction


## Objective

The objective of the game is to earn the most tokens, this is done by playing the plethora of minigames at the players disposal, some of the minigames included


### Sumo

Players face off on a small elevated platform, they must manoeuvre themselves around the platform without being hit off the platform and must also eliminate other players by hitting them off the platform.


### Race

This is a straight race, where the winner is the first player to drive from ‘A’ to ‘B’, First, Second and Third receive tokens.


### Zombie Tag

A Random player is chosen to be a ‘Zombie’ ; they must navigate the small map and infect other players by touching them. When a player is touched they become infected, and now must infect others. The winners are either the players that survive in the given time limit or the first zombie for infecting every other player.


### Balance Beams

This minigame switches up gameplay by allowing the player to control a platform with their ‘Ball’ on the platform, there will be holes in the platform which the player must manoeuvre their ball into the holes to receive points without rolling off the edge.


## Graphics


### Landscape

The Landscape will be viewed through a perspective camera attached to the players ‘Ball’. It will be built with low poly styled assets, giving it a cartoonish and stylized look. The camera can zoom in and out and rotate around the player allowing them to see the entire world.


### Objects

Objects will be modelled in Blender in a low poly stylized way, there will be different modals for each minigame and player accessory


### Screen Display


#### Dashboard

Player boost cooldown will be displayed on the dashboard showing how long until the player is able to boost again. The dashboard will also show the current points earned in each minigame, the time remaining in the minigame and other stats  that will be necessary for the player.


#### Popups

Popups will appear at the top of the screen indicating the rules of the game


#### Weather

Different weather effects will be investigated:



* Snow/Rain - slippery surfaces and less traction, white snow blanket on materials/rain effects
* Sandstorm - Poor visibility, sand dunes across maps


# Development System


## Software

Ball Mania will be developed using Unreal Engine 5.3+, and be developed by Richard McNulty


# Gameplay


## World

The playing world will be small and only encapsulate the current minigame being played, varying in size


## Landscape

Each minigame will include foliage, obstacles, buildings and other visually interesting objects for the player to feel more immersed in the game, they are not intractable by the user.


### Foliage

Foliage will be used for aesthetics and will only contribute to the feel of the game, making it more dense and immersive


### Obstacles

Obstacles may be places in minigames to obscure a players regular route/strategy, they will make the game more intense since the map will always change forcing the player to adapt


## Ground Type

Types of ground will include



* Road
* Ice/Snow
* Inflatable
* Water


## Object Types

Objects which can appear include



* Blockades
* Walls
* Cones
* Ramps


## Control

The game will be controlled by mouse and keyboard or gamepad


### Direct Control



* Roll Forward
* Roll Backward
* Roll Left
* Roll Right
* Boost
* Jump
