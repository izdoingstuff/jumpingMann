

# jumpingMann

jumpingMann is a platform game coded in MIPS Assembly (ASM). The game simulates classic platforming mechanics and requires the **MARS MIPS Assembler** to run. It uses the bitmap display and keyboard MMIO simulator available in MARS for graphical output and input handling.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Gameplay](#gameplay)
- [Controls](#controls)
- [Development](#development)
- [Credits](#credits)

## Requirements

- **MARS MIPS Assembler Simulator** 

## Installation

1. **Download MARS**: Provided in the repository.
2. **Clone this repository**:
   ```bash
   git clone https://github.com/izdoingstuff/jumpingMann.git
   ```
3. **Open the Project in MARS**:
   - Launch MARS and open the `game.asm` file in the project folder.

4. **Setup Display and Keyboard**:
   - Enable the bitmap display with these setting :
   ```
   # Bitmap Display Configuration: 
   - Unit width in pixels: 4 
   - Unit height in pixels: 4
   - Display width in pixels: 256  
   - Display height in pixels: 516 
   - Base Address for Display: 0x10008000 ($gp) 
   ```
   - Enable keyboard MMIO in MARS.

## Gameplay

jumpingMann takes you through a classic platformer experience:
- **Objective**: Guide your character through obstacles, collect items, and reach the goal.

## Controls

- **W, A, S, D Keys**: Move the character.
- **R** : Restart game.
- **Q** : Quit game.

Note: The game uses MARS keyboard MMIO, so ensure you have enabled it in the simulator.

## Development

jumpingMann is developed in MIPS assembly language, leveraging low-level programming principles with graphics and input devices.
fauzan I Zakaria.
