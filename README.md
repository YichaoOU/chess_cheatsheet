# chess_cheatsheet

## Blindspot: chess training from your own games

**Open it: https://yichaoou.github.io/chess_cheatsheet/**

Blindspot reads your chess.com games (or a PGN file), grades every move with Stockfish 10 in your browser, finds the patterns behind your mistakes and turns them into short puzzles and lessons. Your costliest moves are matched to the named pattern behind them, its lesson and Lichess puzzles with the same pattern. Traps & tactics groups everything into chances you missed, traps you fell into and checkmates (missed, or against you): each pattern shows the book example and its variations, then all your own games at the move where it happened. Your openings are grouped by your own system (the London System, the Colle…) with the replies you met, and matched to the well-known traps on your lines, the mistakes you repeat in the opening, and Lichess puzzles from real games in the same opening. It has a daily "Today's 5", a kid mode, lessons from Capablanca's *Chess Fundamentals*, a chess glossary and rating benchmarks.

Everything runs on your device: games are fetched from chess.com's public API by your browser, the engine runs in your browser, and progress is saved in your browser only. Nothing is uploaded.

## Checkmate patterns cheat sheet

[36-checkmate-patterns-A4-large-boards.pdf](36-checkmate-patterns-A4-large-boards.pdf), ref: https://chessfox.com/checkmate-patterns/

## Credits and licences

- Engine: Stockfish 10 (GPL v3), compiled for the browser by stockfish.js 10.0.2 (Nathan Rugg). Source code: https://github.com/nmrugg/stockfish.js (npm package `stockfish@10.0.2`) and https://github.com/official-stockfish/Stockfish. Licence text: [third_party/stockfish/COPYING.txt](third_party/stockfish/COPYING.txt).
- Lessons: J. R. Capablanca, *Chess Fundamentals* (1921), public domain (Project Gutenberg eBook #33870).
- Puzzles, puzzle themes and benchmark games: Lichess database and lila (CC0 1.0). Opening names: lichess-org/chess-openings (CC0).
- Chess glossary: Wikipedia, "Glossary of chess", Wikipedia contributors (CC BY-SA 4.0); definitions shortened.
- Pieces: "Spatial" set by Maurizio Monge (MIT), from Lichess.
- Not affiliated with or endorsed by Chess.com or Lichess.
