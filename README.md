# Hyper Sudoku

> **Status: stub — not yet implemented**

## Description

Standard 9×9 Sudoku with four extra 3×3 shaded regions (positioned symmetrically inside the grid) that must also contain 1–9.

## Files to create

- `board.lua` — game logic, puzzle generator, serialize/load
- `board_widget.lua` — grid rendering and tap gestures
- `screen.lua` — full-screen layout (buttons + board)
- `main.lua` — PluginBase entry point

## Notes

Shares rules with sudoku.koplugin; extend SudokuBoard base or copy and add variant constraints.
