# Contributing to TwinShip

Thank you for your interest in TwinShip! These guidelines apply to all repositories in the [twinship-eu](https://github.com/twinship-eu) organisation unless a repository provides its own `CONTRIBUTING.md`.

By participating you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

- **Report bugs.** Open an issue in the affected repository using the *Bug report* form.
- **Suggest improvements.** Open an issue using the *Feature request* form. For ontology changes, describe the concept, its definition and how it relates to existing classes and properties.
- **Improve documentation.** Fixes to READMEs, examples and docstrings are always welcome.
- **Contribute code or ontology modules** through a pull request (see below).

Please search existing issues before opening a new one. If you have found a **security vulnerability**, do **not** open a public issue; follow the [security policy](SECURITY.md) instead.

## Pull request workflow

1. **Discuss first.** For anything beyond a small fix, open or comment on an issue so we can agree on the approach before you invest time.
2. **Fork** the repository (external contributors) or **create a branch** (consortium members) from `main`. Use a descriptive branch name, such as `fix/shacl-shape-for-propeller` or `feat/weather-module`.
3. **Follow the repository's conventions.** Each README explains how to set up the project, run the tests and run the linters or formatters (for example `uv run pytest` and `uv run ruff check .` for the Python projects).
4. **Keep changes focused.** One logical change per pull request makes review faster.
5. **Write clear commit messages** in the imperative mood ("Add hull resistance property", not "Added…").
6. **Open the pull request** against `main`, fill in the template, link the related issue (`Closes #123`) and make sure all checks pass.
7. **Address review feedback.** At least one maintainer approval is required before merging.

## Ontology contributions

For changes to the [TwinShip ontology](https://github.com/twinship-eu/twinship-ontology):

- Reuse existing classes and properties, or established external vocabularies, before introducing new terms.
- Give every new term a label and a definition.
- Add or update SHACL shapes and example data where relevant.
- Regenerate the documentation build locally to check that nothing breaks.

## Licensing

Contributions are accepted under the license of the repository you are contributing to (see its `LICENSE` file). By submitting a pull request you confirm that you have the right to license your contribution under those terms.

## Questions

See [SUPPORT.md](SUPPORT.md) or contact us at [info@twin-ship.eu](mailto:info@twin-ship.eu).
