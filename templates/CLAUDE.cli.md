# CLAUDE.md

## Project
Python CLI, stdlib first, argparse based.

## Commands
- run: `python -m app --help`
- test: `python -m pytest -q`

## Rules
- Every flag gets a help string.
- Exit codes: 0 ok, 1 runtime error, 2 usage error.
- No prints in library code, only in main().
