# alexis-gavin

# dd20

This program simulates D&D dice rolling, or any other
games with complex dice systems. It is highly extensible
for custom needs and behavior. 

## Installation 

**Python 3+ required for installation**

Use package manager [pip](https://pip.pypa.io/en/stable/) to install dd20

```bash
pip install dd20
```

## Usage 

```python
import dd20

diceRoll = dd20.roll(1dd20+15)
str(diceRoll) # returns string for dice roll
diceRoll.total # returns total of roll
```

## Contributing 

Pull requests are welcome. When making changes be sure to:

1. Update the README.md with your changes 
2. Update tests as appropriate 