# Github Atom Editor config

The contents of my `~/.atom`, with the addition of a `packages.txt`.

## Installation

*Doing this will overwrite existing configuration.*

1. Pull files into local `.atom/`
2. Install APM packages: `apm install --packages-file packages.txt`

## Updating `packages.txt`

This really should be built-in to APM, but...

```bash
# Compare contents to installed packages
diff packages.txt <(apm ls -ib)

# Write new packages.txt
apm ls -ib > packages.txt
```
