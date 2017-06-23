# git-extras

> A collection of git functions.

## Getting Started

1. Clone this repo.
1. Add the following to your `.gitconfig` file:
```git-config
[include]
  # Don't seriously copy-paste and be done. You will need to update the path.
  path = ~/path/to/git-extras.git/aliases.gitconfig
```
1. Add the following to your execution `PATH` in wherever you manage your execution `PATH`:
```bash
# Don't seriously copy-paste and be done. You will need to update the path.
export PATH="${PATH}:~/path/to/git-extras.git/bin"
```
1. Reload your session, profile file, etc.

### Optional Bits

The following commands have a dependency on an external project to do things and stuff and junk. If the dependency is not installed, it will present an error.

| Command | Dependencies |
|---|---|
| `git-commit-all-from` | [commit-from][] from [NPM][] |
| `git-commit-from` | [commit-from][] from [NPM][] |

[commit-from]: https://www.npmjs.com/package/commit-from
[NPM]: https://www.npmjs.com/
