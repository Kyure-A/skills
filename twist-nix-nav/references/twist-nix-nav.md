# Twist Nix Navigation Map

## Repository Path

- Prefer a local checkout path from the user.
- Common ghq path: `~/ghq/github.com/emacs-twist/twist.nix`.

## Entry Points

- `README.org`: high-level overview and project scope.
- `flake.nix`: flake outputs and entry points.
- `lib/default.nix`: public library functions and helpers.
- `pkgs/default.nix`: package set entry and wiring.
- `pkgs/emacs/default.nix`: core configuration function and arguments.
- `pkgs/overlay.nix`: deprecated overlay API.

## Modules

- `modules/home-manager.nix`: Home Manager module options and wrapper packaging.

## Build Support

- `pkgs/build-support/`: helpers for parsing and metadata.
- `pkgs/build-support/elisp/`: parsing of elisp headers, setup, and use-package.
- `pkgs/emacs/build/`: build logic for elisp packages.
- `pkgs/emacs/data/`: inventory and archive data plumbing.
- `pkgs/emacs/lock/`: lockfile generation and helpers.
- `pkgs/emacs/tools/`: dependency checks and reverse dependency tools.

## Tests and Examples

- `test/twist.nix`: example configuration (registries, input overrides).
- `test/home.nix`: Home Manager test config.
- `test/init.el`: elisp input example.
- `test/early-init.el`: early init example.
- `test/flake.nix`: integration test flake.

## Search Hints

- `rg -n "identifier" <repo>` to locate definitions.
- `rg -n "optionName" modules/home-manager.nix` for HM options.
