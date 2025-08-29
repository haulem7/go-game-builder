# Go Game Builder

A Python utility for managing, compiling, and packaging Go game projects.

## Features
- Finds all directories containing "game"
- Copies and organizes them into a target folder
- Compiles Go source code automatically (`go build .`)
- Generates a `metadata.json` with game names and count

## Requirements
- Python 3.7+
- Go installed and available in your system path

## Usage
```bash
# Clone the repo
git clone <your-repo-url>
cd go-game-builder

# Run the script
python main.py <source_dir> <target_dir>
