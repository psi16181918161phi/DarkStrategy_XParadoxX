# Security Policy

## Supported Versions

`X Paradox X` is currently in active hackathon-stage development (LabLab AI Factory / Natively AI, 2026-08-03 to 2026-08-10) and has not yet reached a tagged `1.0.0` release. Security fixes are applied to the `main` branch only until a formal release cadence is established.

| Version | Supported |
| ------- | --------- |
| `main` (pre-release / hackathon build) | :white_check_mark: |
| Any tagged release prior to `1.0.0` | :x: |

This table will be revised once versioned releases begin, per `game_specifications/015_game_deployment.txt`.

## Reporting a Vulnerability

We take the security of `X Paradox X` and its Python backend seriously. If you discover a security vulnerability, **please do not open a public GitHub issue**.

Instead, report it privately using one of the following channels, in order of preference:

1. **GitHub Private Vulnerability Reporting** — Use the "Report a vulnerability" button under the **Security** tab of this repository (`psi16181918161phi/DarkStrategy_XParadoxX`). This is the preferred channel and creates a private advisory visible only to maintainers.
2. **Direct maintainer contact** — Open a private message to the maintainer, `@psi16181918161phi`, on GitHub if the Security tab is unavailable to you.

Please include as much of the following as possible:

- A clear description of the vulnerability and its potential impact;
- Steps to reproduce, proof-of-concept code, or a minimal reproduction case;
- The affected file(s), module(s), or commit/branch;
- Any known mitigations or workarounds.

### What to expect

| Stage | Target Timeline |
| ----- | ---------------- |
| Initial acknowledgement | Within 5 business days |
| Triage and severity assessment | Within 10 business days of acknowledgement |
| Fix or mitigation plan communicated to reporter | Within 30 days of triage, severity-dependent |
| Public disclosure (coordinated with reporter) | After a fix is released, or by mutual agreement |

These are target timelines for a small, hackathon-stage project, not contractual SLAs.

### Scope

In scope:

- The Python backend implementing the `X Paradox X` rules engine, game state management, and any networked/multiplayer components introduced per `game_specifications/016_game_modes.txt`;
- Build, packaging, and CI/CD configuration under `game_specifications/014_game_cicd.txt` and `015_game_deployment.txt`;
- Dependency and supply-chain issues (e.g., vulnerable third-party packages declared in the project's virtual environment per `game_specifications/007_game_virtual_env.txt`).

Out of scope:

- Game-balance issues, exploits of intentional game mechanics, or AI-adviser behavior that is undesirable but not a security vulnerability;
- Denial-of-service reports that require unrealistic resource assumptions;
- Issues in third-party dependencies that are already publicly disclosed and awaiting an upstream fix (please report those upstream instead).

### Disclosure Policy

We follow **coordinated disclosure**: please give us a reasonable opportunity to investigate and remediate an issue before any public disclosure. We will credit reporters (unless anonymity is requested) once a fix is released, consistent with the attribution terms in [LICENSE.md](LICENSE.md).

### Safe Harbor

We will not pursue legal action against security researchers who make a good-faith effort to comply with this policy, report privately, avoid privacy violations and data destruction, and give us reasonable time to remediate before any public disclosure.
