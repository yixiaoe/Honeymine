# Honeymine - Hexagonal Minesweeper

## Tech Stack
- **Language:** C++17
- **Graphics:** SFML 2.6
- **Build:** CMake
- **Platforms:** Windows, macOS, Linux

## Installation
```bash
git clone https://github.com/yixiaoe/Honeymine.git
cd Honeymine
mkdir build && cd build
cmake .. && cmake --build .
./bin/Honeymine
```

## Gameplay
- **Left-click:** Reveal hexagon
- **Right-click:** Place/remove flag
- **R key:** Reset game
- **Goal:** Reveal all safe hexagons without hitting mines
- **Numbers:** Show adjacent mine count
- **First click:** Always safe!

*(Hexagonal grid provides 6-directional neighbor relationships for a fresh challenge)*
