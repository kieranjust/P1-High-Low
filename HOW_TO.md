# Git process

```shell script
mkdir High-Low
cd High-Low
git init .
git remote add origin https://github.com/oscarrojasreyes/P1-High-Low.git
git pull origin main
git checkout main

git checkout -b MyBranch


```

# sample python highlight

```python
import random


class HighLow:
    """ROCK IT!!!"""

    def __init__(self):
        """Init Test"""
        self.secretNumber = 0
        self.tries = 5
        self.difficulty = 0
        self.range = 0
        self.guessed = False
```