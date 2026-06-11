# Quiz Game 

A command-line Python quiz engine that presents multiple-choice questions, validates input, tracks score, and assigns a final grade. Built as a group project at NUST.

---

## How to Run

**Requirements:** Python 3.x — no external libraries needed.

```bash
python quiz_game.py
```

---

## Concepts Applied

- **Nested dictionaries** — quiz data stored as dict of lists of dicts
- **Nested loops** — outer loop iterates questions, inner loop prints options
- **Input validation loop** — `while True` re-prompts until valid answer entered
- **Score tracking** and percentage calculation
- **Grade classification** with if-elif logic

---

## Data Structure

```python
quiz = {
    "version_id": [
        {
            "q": "Question text",
            "opt": {"a": "...", "b": "...", "c": "...", "d": "..."},
            "ans": "correct_key"
        }
    ]
}
```

Adding new questions requires only extending the dictionary — no changes to game logic needed.

---

## Project Context

Group project at NUST (BS Bioinformatics) to practice nested data structures and iterative program control. Deliberately separates data from logic — a foundational software design principle.

---

## Files

```
quiz_game.py
README.md
```
