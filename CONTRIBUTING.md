# Contributing to Plasma

Thanks for your interest in Plasma — the open-source real-time intelligence platform. This guide applies across all repositories in the [`plasmash`](https://github.com/plasmash) organization.

## Ways to contribute

- **Report bugs** and request features via the relevant repository's issues.
- **Ask questions / share ideas** in [Discussions](https://github.com/orgs/plasmash/discussions).
- **Improve docs** — both repository READMEs and [docs.plasma.sh](https://docs.plasma.sh).
- **Submit code** — fixes, new components, or new packages.

## Project layout

- **Toolchain** — the `plasmactl` CLI and its plugins (`plasmactl-model`, `plasmactl-component`, `plasmactl-platform`, `plasmactl-node`, `plasmactl-topology`, `plasmactl-processors`). Mostly Go.
- **Packages** — domain bundles of components (`plasma-core`, `plasma-work`, …), published progressively.
- **Models** — platform compositions built from packages (e.g. `ta`, The Agency).

See [docs.plasma.sh](https://docs.plasma.sh) for the architecture and concepts.

## Development setup

Install the CLI:

```sh
curl -sSL https://get.plasma.sh | sh
```

Prerequisites: Docker and Git (Linux, macOS, or Windows). For Go plugins you'll also need a recent Go toolchain.

## Pull requests

1. Fork the repository and create a topic branch from the default branch.
2. Keep changes focused; one logical change per PR.
3. Use **[Conventional Commits](https://www.conventionalcommits.org/)** for commit messages (`feat:`, `fix:`, `refactor:`, `docs:`, …). Keep history clean — no "wip" commits.
4. Make sure builds/tests pass and update docs when behavior changes.
5. Open the PR with a clear description of the what and why.

## Code of conduct

Be respectful and constructive. Harassment or abusive behavior is not tolerated.

## License

Plasma is licensed under the **[EUPL-1.2](LICENSE)**. By contributing, you agree that your contributions are licensed under the same terms. The EUPL is copyleft, OSI-approved, and compatible with GPL and other major licenses.
