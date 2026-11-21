# Git Laboratory Work

## Git aliases

| Alias | Command |
|---|---|
| git st | git status |
| git ci | git commit |
| git co | git checkout |
| git br | git branch |
| git df | git diff |
| git lg | git log --oneline --decorate --all --graph |
| git recent | git log --oneline -n 5 |

Aliases simplify frequently used Git commands.

## CI/CD Laboratory Work 2

This Python project demonstrates basic arithmetic operations.

### Supported operations
- Addition
- Subtraction
- Multiplication

### Running tests
python -B -m unittest discover -p "test_*.py"

### CI/CD
GitHub Actions automatically runs unit tests on push and pull requests.
HTML API documentation is generated using pydoc.
