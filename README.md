# X Paradox X

**Company:** X Dark X &nbsp;|&nbsp; **Genre:** Dark Strategy (DS) &nbsp;|&nbsp; **Status:** Hackathon-stage development

A two-player, local pass-and-play digital tabletop strategy game that fuses standard chess pieces and movement, a standard 52-card deck reinterpreted as an ability system, six-sided dice combat resolution, and Monopoly-style territory and economy on a variable-size square board.

Built for the **LabLab AI Factory** hackathon using **Natively AI**. This repository (`DarkStrategy_XParadoxX`, a `py.typed` Python package) is the authoritative backend implementation, not a disposable planning artifact.

## Table of Contents

- [About](#about)
- [Documentation](#documentation)
- [Getting Started](#getting-started)
- [Project Status](#project-status)
- [Contributing](#contributing)
- [Security](#security)
- [License](#license)

## About

See [ABOUT.md](ABOUT.md) for the full brand identity, elevator pitch, and project origin.

## Documentation

All game design and engineering specifications live in [`game_specifications/`](game_specifications/), governed by a binding documentation standard (`0000_documentation_standards.txt`). Start at the master index:

- [`game_specifications/000_index.txt`](game_specifications/000_index.txt) \u2014 full document map
- [`game_specifications/001_game_concept.txt`](game_specifications/001_game_concept.txt) \u2014 brand, concept, MVP scope
- [`game_specifications/017_game_rules.txt`](game_specifications/017_game_rules.txt) \u2014 authoritative rules engine

## Getting Started

1. Set up the Python virtual environment per [`game_specifications/007_game_virtual_env.txt`](game_specifications/007_game_virtual_env.txt).
2. Review the repository scaffolding in [`game_specifications/006_game_scaffolding.txt`](game_specifications/006_game_scaffolding.txt).
3. Review coding standards in [`game_specifications/005_game_coding_standards.txt`](game_specifications/005_game_coding_standards.txt) before opening a Pull Request.

## Project Status

Active hackathon-stage development (LabLab AI Factory / Natively AI). No versioned release has shipped yet; see [SECURITY.md](SECURITY.md) for the supported-version policy and [`game_specifications/015_game_deployment.txt`](game_specifications/015_game_deployment.txt) for the deployment plan.

## Contributing

Contributions are welcome via **mandatory fork-and-Pull-Request** (direct pushes to upstream are not accepted). See [CONTRIBUTION.md](CONTRIBUTION.md) for the full workflow, coding standards, and testing requirements.

## Security

To report a vulnerability, do not open a public issue \u2014 see [SECURITY.md](SECURITY.md) for the private reporting process.

## License

X Paradox X is source-available under a modified **CC BY-NC 4.0** license with proprietary supplementary terms, including a mandatory-fork contribution-tracking policy. See [LICENSE.md](LICENSE.md) for full terms.
