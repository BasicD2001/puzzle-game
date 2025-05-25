# 🚰 Pipe Puzzle Game - Java AWT

This is a **logic-based puzzle game** developed in **Java**, featuring a custom graphical user interface built using **Java AWT** (same base setup as Tetris). The objective is to rotate and place pipe pieces on a grid in such a way that a **complete, non-blocked water pipeline** is formed — with **no dead ends**.

## 🧠 Game Concept

The game consists of a grid where each cell can contain a **pipe segment**. The player must:

- Rotate and position pipe segments (elbows, straights, T-junctions, etc.)
- Ensure that **all open ends connect** to another pipe
- Avoid any **dead-end segments**
- Complete the entire path for the water to flow properly from start to end

Inspired by classic puzzle mechanics (similar to games like Pipe Mania or Plumber), this game tests spatial reasoning and planning.

## 🛠️ Technologies Used

- **Java SE**
- **AWT (Abstract Window Toolkit)** – for rendering GUI
- **Java Event Handling** – for mouse/keyboard interactions
- **Custom game logic and grid management system**

## 🧩 Features

- Interactive grid with selectable pipe segments  
- Pipe rotation and placement using mouse or keyboard  
- Real-time rendering of pipe connections  
- Win condition detection (valid pipe network)  
- Reset / new puzzle generation
