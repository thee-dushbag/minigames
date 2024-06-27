# MiniGames <sub><sub>🏓</sub></sub>

<style>
:root { font-family: sans-serif; }
</style>

<small><em>Games as State Machines</em></small>

## Introduction

Games, aren't they wonderful? How do they work? Well, in this repo I intend to create simple games as simple _State Machines_.

A Game can be treated like a black box that takes in signals from the environment and reacts to them by modifying and updating its state, hence, _state machine_.

## Example

Take a simple game like _Ping Pong_, the ball has a position, a direction it is moving and speed at which it moves. These and a few more states represent the game, therefore, this game can be created by just modifying various states and checking for some conditions along the way.

Interestingly, how user input is collected or how the game is presented to the user is abstracted away, what we simply expect is correct input.
