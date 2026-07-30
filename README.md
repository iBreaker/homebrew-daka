# Homebrew Tap for Daka

This is the official Homebrew tap for
[Daka](https://github.com/iBreaker/daka), a native macOS menu bar tracker for
daily clock-in span.

## Install

```bash
brew install iBreaker/daka/daka
brew services start iBreaker/daka/daka
```

Open the dashboard:

```bash
daka --show
```

## Upgrade

```bash
brew update
brew upgrade iBreaker/daka/daka
brew services restart iBreaker/daka/daka
```

## Stop and uninstall

```bash
brew services stop iBreaker/daka/daka
brew uninstall iBreaker/daka/daka
```

Configuration and clock records are preserved in:

```text
~/Library/Application Support/Daka/
```

See the [main project documentation](https://github.com/iBreaker/daka#readme)
for setup, permissions, usage, backups, and troubleshooting.
