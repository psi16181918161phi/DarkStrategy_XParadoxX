# About X Paradox X

## Company

**X Dark X** — the studio banner under which this project is published.

## Genre

**Dark Strategy (DS)** — a genre defined by this project as the deliberate synthesis of positional tactics, hidden-information ability resolution, dice-driven uncertainty, and territorial economy into a single ruleset. Every future title under the X Dark X banner is expected to sit inside this genre unless a new genre document is separately ratified (see `game_specifications/001_game_concept.txt §1.6`).

## Title

**X Paradox X** — a two-player, local pass-and-play digital tabletop strategy game.

## Elevator Pitch

X Paradox X fuses four previously separate systems into one board:

- **Chess** — standard piece set and movement rules, scaled to a variable-size square board (4x4 minimum, up to 8x8 or custom).
- **Playing cards** — a standard 52-card deck reinterpreted as an ability system, where suit determines class (Hearts = Defence, Spades = Attack, Diamonds = Economy, Clubs = Chaos) and rank determines magnitude.
- **Dice** — six-sided dice combat resolution (Attack + d6 vs. Defence + d6).
- **Territory and economy** — Monopoly-style ownership, upgrades, and Dominion Points.

Victory is achieved through territorial majority, King capture, or accumulating 20 Dominion Points. The full ruleset is authoritative in `game_specifications/017_game_rules.txt`.

## Origin

X Paradox X began as an ideation session recorded in `chatGPT_records/chat_record_30072026.md` and was subsequently reconciled, locked, and formalized into the `game_specifications/` corpus — a 25-file, fully cross-referenced specification governing both the game design and the Python backend engineering standards. See `game_specifications/000_index.txt` for the complete document map, and `game_specifications/001_game_concept.txt §1.8` for the full reconciliation diff between the original ideation and the locked canon.

## Hackathon Context

This repository is the real, shipping Python backend (marked `py.typed`, not a disposable planning artifact) submitted to the **LabLab AI Factory** hackathon, built using **Natively AI**. See `game_specifications/0001_natively_ai_prompt.txt` for the opening-day master prompt and delivery pacing plan.

## Project Status

Active, hackathon-stage development. See `game_specifications/014_game_cicd.txt` and `015_game_deployment.txt` for the CI/CD and release process, and [SECURITY.md](SECURITY.md) for the current supported-version policy.

## License

X Paradox X is source-available under a modified CC BY-NC 4.0 license with proprietary supplementary terms. See [LICENSE.md](LICENSE.md) for the full terms, including the mandatory-fork contribution policy.

## Contributing

See [CONTRIBUTION.md](CONTRIBUTION.md) for the fork-and-Pull-Request workflow, coding standards, and testing requirements.

## Learn More

- Full specification index: `game_specifications/000_index.txt`
- Game concept and brand identity: `game_specifications/001_game_concept.txt`
- Rules engine (single source of truth for mechanics): `game_specifications/017_game_rules.txt`
