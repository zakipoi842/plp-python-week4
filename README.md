# Week 4 Python Assignment — Functions

Two short Python programs that practise defining functions, passing parameters, returning values, and using default parameter values.

## Files

- `welcome.py` — defines one `welcome(name)` function that returns a greeting sentence, then calls it three times with different names.
- `toolbox.py` — three small functions: `double(number)` returns a number times 2, `is_pass(score)` returns True if the score is 50 or more, and `greet(name, greeting="Hello")` returns a greeting with an optional custom greeting.

## The hardest function to write

The hardest one was `greet(name, greeting="Hello")` because it needed a **default value** for the second parameter. It took a moment to understand that the default only kicks in when you don't pass the second argument — calling `greet("Brian", "Habari")` overrides it, while `greet("Amina")` uses `"Hello"` automatically.

## How to run

    python3 welcome.py
    python3 toolbox.py

## Expected output

`welcome.py`:

    Hello, Amina! Welcome to PLP.
    Hello, Brian! Welcome to PLP.
    Hello, Fatuma! Welcome to PLP.

`toolbox.py`:

    14
    20
    True
    False
    Hello, Amina!
    Habari, Brian!

## Author

Zakariye Ali Mursal
PLP 2026