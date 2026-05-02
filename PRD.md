# PRD: pythoncrash

## Overview
A collection of Python "crash course" scripts demonstrating fundamental programming concepts through progressive examples. Six numbered files (`one.py` through `six.py`) each likely cover a distinct topic (variables, control flow, functions, data structures, etc.). An educational resource for Python beginners, organized as a sequential learning path.

## Goals
- Provide runnable Python examples for core language features
- Progress from basic to slightly more advanced concepts across 6 files
- Be self-contained — each file runs independently

## Non-Goals
- Complete Python tutorial
- Exercises or graded assignments
- Web framework or library usage
- Production code patterns

## User Stories
- As a Python beginner, I want working code examples I can run and modify to understand the language.
- As an instructor, I want shareable standalone scripts for a crash course session.

## Tech Stack
- **Language**: Python 3.x
- **Libraries**: stdlib only

## Architecture
```
pythoncrash/
├── one.py    # Topic 1 (e.g., variables, print, basic types)
├── two.py    # Topic 2 (e.g., conditionals, loops)
├── three.py  # Topic 3 (e.g., functions)
├── four.py   # Topic 4 (e.g., lists, dicts)
├── five.py   # Topic 5 (e.g., file I/O or OOP basics)
└── six.py    # Topic 6 (e.g., more advanced topic)
```

## Deployment / Run
```bash
python one.py
python two.py
# etc.
```
No installation needed beyond Python 3.

## Constraints & Notes
- **Sequential**: intended to be read and run in order (one → six)
- **Educational only**: code may use non-idiomatic patterns for clarity
- **No tests**: scripts are demonstration-only, no test suite
