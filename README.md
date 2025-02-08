# Folder Renaming Script

## Overview
This script renames folders in `C:\Users\Siva\Pictures` that follow the `DD-MM-YYYY` or `D-MM-YYYY` format and converts them to `YYYY MM DD`.
The goal is to standardize folder naming for better organization and sorting.

## Example
Before running the script:
```
5-12-2024
7-02-2025
```
After running the script:
```
2024 12 05
2025 02 07
```

## How It Works
- The script scans the directory for folders matching the `DD-MM-YYYY` or `D-MM-YYYY` pattern.
- It extracts the **day**, **month**, and **year** components.
- The new folder name is formatted as `YYYY MM DD` with zero-padded day and month values.
- The folder is renamed accordingly.

## Usage
Run the `.exe` file:

## License
This project is licensed under the MIT License. See `LICENSE` for details.

Written with ChatGPT
