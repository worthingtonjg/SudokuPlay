# Sudoku Win8 — Unity prototype

[Play in your browser](https://worthingtonjg.github.io/SudokuPlay/)

A foundational Unity port of Jonathan Worthington's Windows Sudoku game. Select a blank cell, then use the keypad or number keys. N toggles notes; Z undoes the last action. Includes hints, checks, pause and local browser saves.

This repository contains compiled WebGL output only. Source is private. Releases are copied here manually after validation; source changes do not deploy automatically.

The original four difficulty levels and seed bank are retained, with one owner-approved repair: Hard seed #5 gains r1c3=7 (28 to 29 clues) so all 20 puzzles have a unique solution. That puzzle may be slightly easier.

This is a prototype. Original themes, artwork, localization and exact Windows layout are not yet ported. Desktop browser play is tested; phone ergonomics and screen-reader accessibility remain future work. Undo does not survive reload. Local saves can be lost if browser data is cleared. No ads, analytics, accounts or cloud saves.

See BUILD-IDENTITY.json for the source commit and compiled-file hashes, and NOTICE.txt for notices.

