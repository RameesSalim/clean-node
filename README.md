# clean-node

Find and delete `node_modules` folders to free disk space.

## Install

```bash
brew tap rameessalim/tap
brew install clean-node
```

## Usage

```
clean-node [path] [options]
```

### Options

| Flag              | Description                                  |
| ----------------- | -------------------------------------------- |
| `-n`, `--dry-run` | List matches and total size without deleting |
| `-y`, `--yes`     | Delete all matches without prompting         |
| `-h`, `--help`    | Show help                                    |

### Examples

```bash
# Scan current directory, prompt before each deletion
clean-node

# Scan a specific path
clean-node ~/projects

# Preview what would be deleted
clean-node ~/projects --dry-run

# Delete everything without prompting
clean-node ~/projects --yes
```

## License

MIT
