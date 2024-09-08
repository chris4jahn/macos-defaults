# macOS Defaults Export/Import Scripts

This repository contains two bash scripts to export and import macOS defaults (`plist`) files across different locations such as Dropbox, iCloud, Box, WorkDocs, or a custom directory. These scripts provide flexibility with various storage options or custom paths.

## Scripts

1. **export_defaults.sh**: Exports all macOS defaults into `.plist` files.
2. **import_defaults.sh**: Imports previously exported `.plist` files back into macOS defaults.

### Prerequisites

- These scripts require macOS and the use of the `defaults` command.
- Ensure you have permissions to read/write in the specified directories.

---

## Usage

### export_defaults.sh

The `export_defaults.sh` script exports macOS defaults to the specified directory. If no directory is specified, it defaults to `~/.config/defaults`.

```bash
./export_defaults.sh [custom_output_directory] [options]
