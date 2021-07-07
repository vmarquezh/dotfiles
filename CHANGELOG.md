# Changelog

Change log for Víctor Márquez Dotfiles

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changeliog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]
### Added
- Adds PATH to bashrc.
- Adds `vmDebug` variable check to enable debugging in `bashrc`.
- Adds suport to call private, local and work Dotfiles.
- Adds `fmt75` `fmt80` and `fmt85` scripts to reflow text blocks.
- Adds `acrobat`script. Calls Windows-side Acrobat.
- Adds `weather` script to show weather forecasts in terminal.
- Adds `git-current-branch-to-master-and-push` script.
- Adds `notes-changed` script to show changes pending to commit from zet-style repos.
- Adds `towinpath` script to transform WSL paths to Windows paths.
- Adds `sanitize` script to sanitize strings for file-name safe/conformance.
- Adds colors, dircolors and termcap-colors.

### Changed
- Commented-out everything perl-depending and per-related from `vim/vimrc`.
- setup scripts: Small changes.
- `git-subtrees` code refactoring.
- `vimrc` disabled line numbers.
- Removed `zet` and `note` scripts/aliases (moved to Simple Zet project).

### Fixed
- Fixes Vim's ModeMsg was invisible (changed it's color).

## [1.0-alpha.1] - 2021-06-23
### Added
- Added `shell.d/bashrc`. My Dotfiles entry point, called from `~/.bashrc`.
- Added `config-default.sh`.
- Added `isosec` script. Echoes UTC date/time in 'YYYYMMDDhhmmss' format.
- Added `urlencode` script. Echoes the input as URL Encoded.
- Added `setup` script.
- Added `simple-zet` setup script to integrate Simple Zet to my Dotfiles.
- Added `shell.d/bash_aliases` w/some common and Git aliases.
- Added `git-subtrees` script. Gets a list of subtrees added to a Git repo.
- Added `vim/vimrc` and it's setup script.


[Unreleased]: https://github.com/vmarquezh/dotfiles/compare/v1.0-alpha.1...HEAD
[1.0-alpha.1]: https://github.com/vmarquezh/dotfiles/releases/tag/v1.0-alpha.1

