---
layout: default
title: Wordle
---

# Wordle - Terminal Edition

## Overview

A simple, terminal-based implementation of Wordle. This game replicates the mechanics of the original Wordle, including simulating color-coded feedback for guesses, robust input validation, and handling edge cases like repeated letters.

## Inspiration

This project was created as a way to practice my Python skills. I was determined to follow all of the rules for the game so that it would behave the same as the original.

## Development Process

This project was built entirely in Python. I started with the basic functionality, like getting in the guesses and checking that they were correct. I would test out with that day's Wordle puzzle in the real world, replicating my moves to double check they worked the same. I even downloaded another Wordle app and used that to help with testing, verifying that my output was correct.

It was extremely important to me that this game worked for *every* situation. Perhaps the answer has one 'E' but the user guessed an answer with two; I ensured that my game would only mark one 'E' as correct.

## Features

* Since I can't do color-coding in the terminal, I use boxes with === to indicate yellow (correct letter, incorrect location) and ### for green (correct letter, correct location).

* On-Screen Keyboard: This wasn't part of my original plan, but I included the same functionality of the real keyboard in Wordle. Letters that are not in the solution disappear. Since I don't have colors to indicate which letters are green or yellow, I show the letters as capitalized when they have been correctly guessed.

* Rigorous testing: I wasn't going to let this game be complete until it worked for all types of words. I had friends test it out too so it wasn't just me testing it.

## What I learned

This was the perfect project for practicing Python. It allowed me to think creatively. How can you implement a game in the terminal with the same functionality of the real game? I thought about edge cases like never before.

## Try It Out

You can clone my project [here](https://github.com/sarahmarie23/Wordle) and try it out for yourself!