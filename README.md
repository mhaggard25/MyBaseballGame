# ⚾ Baseball: The Game

A simple, retro-inspired baseball game built for the browser.

The goal is to create a baseball game based on **decisions, dice rolls, and game state** rather than physics or simulation. Think of an old 1990s PC baseball/tabletop game brought back with a modern web interface.

## 🎮 The Idea

This isn't trying to be MLB The Show.

There are no realistic physics engines, 3D stadiums, or 400-button control schemes.

Instead, the game is built around:

- ⚾ Baseball decisions
- 🎲 Dice rolls
- 📊 Player and team statistics
- 🧠 Strategy
- 🏟️ Simple game state
- 🖥️ A retro PC-game interface

The player makes a decision, the game rolls the dice, and the result changes the game.

## 🖥️ Visual Style

The game will use a **1990s PC game aesthetic** inspired by the later versions of games like *The Oregon Trail*.

The goal is:

- Retro Windows-era interface
- Real photographs or photo-like imagery
- Simple menus and controls
- A baseball field image as the visual centerpiece
- Clean information panels
- A slightly cheesy "old computer game" feeling

Basically:

> What if somebody made a baseball board game for Windows 95?

## 🛠️ Technology

The game is being built with:

- **HTML** — game structure
- **CSS** — visual design
- **JavaScript** — game logic
- **Git** — version control

The project is intentionally being kept simple so that the game can eventually be played directly in a web browser.

## ⚾ Planned Game Structure

The basic interface will contain:

```text
┌──────────────────────────────────────────────────────────┐
│  ⚾ BASEBALL                                              │
│     THE GAME                                              │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  HOME: GUNNERSVILLE          AWAY: BIRMINGHAM            │
│                                                          │
│  ┌───────────────────────────────┐   ┌───────────────┐   │
│  │                               │   │   SCOREBOARD   │   │
│  │                               │   │               │   │
│  │        BASEBALL FIELD         │   │  AWAY   3     │   │
│  │                               │   │  HOME   2     │   │
│  │                               │   │               │   │
│  │                               │   │  INNING  5    │   │
│  │                               │   │  OUTS    1    │   │
│  │                               │   └───────────────┘   │
│  └───────────────────────────────┘                       │
│                                                          │
├──────────────────────────────────────────────────────────┤
│  BATTER: #24 MIKE DAVIS                                  │
│  2-3   HR   2 RBI                                        │
│                                                          │
│  [ PITCH ]    [ STEAL ]    [ BUNT ]    [ INFO ]          │
├──────────────────────────────────────────────────────────┤
│  BALL ●●○     STRIKE ●○○     OUT ●                       │
└──────────────────────────────────────────────────────────┘