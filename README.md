# Git Repositories Update

A script to update all GIT repositories in the current folder.

## Installation

Just create a symlink in your folder containing all your Git repositories.

```bash
ln -s git-repositories-update/repo-update.sh update
```

## Usage

```bash
./update
```

Or if you're sure to update every repo, you can force to yes:

```bash
./update -f
```
