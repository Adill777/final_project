# final_project
# Password Strength Analyzer & Wordlist Generator

A beginner-friendly Python tool to:

- Analyze password strength using entropy estimation.
- Generate custom password wordlists using personal inputs (e.g., name, pet, year).
- Demonstrate how weak and guessable passwords can be identified.

---

## Features

- ✅ Password strength estimation using [`zxcvbn`](https://github.com/dropbox/zxcvbn)
- ✅ Feedback on guessability, crack time, and suggestions
- ✅ Custom wordlist generation using:
  - Personal inputs (name, birth year, etc.)
  - Leetspeak patterns (e.g., `a` → `@`, `o` → `0`)
  - Year combinations (`adil2002`, `2002adil`, etc.)
- ✅ Command-line interface (CLI)
- ✅ Wordlist exported as `.txt` file

---

## Requirements

- Python 3.6+
- zxcvbn-python
- argparse

### Installation

```bash
python3 -m venv venv
source venv/bin/activate
pip install zxcvbn argparse
