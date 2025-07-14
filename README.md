# Pokémon Back and Forth

**Pokémon Back and Forth** is a fast-paced browser-based game where players take turns naming Pokémon. The game supports two modes: Person vs Robot and Person vs Person on the same device.

## Game Modes

### 1. Person vs Robot

Challenge a computer opponent that knows every Pokémon from Generation 1 through Generation 9.

- The robot chooses valid Pokémon without repeats.
- One mistake or duplicate entry results in a loss.
- You must answer within a 10-second time limit.

**Folder:** `person-vs-robot/`  
**Entry File:** `robot.html`  
**Data Source:** `data/pokedex.json`

### 2. Person vs Person (Same Device)

Play locally with a friend by taking turns on the same device. Input valid Pokémon names before time runs out.

- Each player takes turns entering names.
- No duplicate Pokémon allowed.
- Time limit of 10 seconds per turn.

**Folder:** `pokemon-duel/`  
**Entry File:** `SameDevice.html`  
**Data Source:** `data/pokedex.json`

## Features

- Real-time 10-second countdown timer
- Turn-based gameplay logic
- Tracks used Pokémon to avoid duplicates
- Scoreboard for each player
- Victory and loss messages
- Simple UI with dynamic updates

## Folder Structure

