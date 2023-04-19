Behind the scenes Magic is really just a programming language that can take in data from the world and the spell caster(s) and can output / interact with the physical world or metaphysical world.

An important note is that magic power available 

# Grammar

This language is easily described as a cross between C and Python but simplified to the core elements.


```
'DEFINE' 'TYPE' ['SUSTAIN', 'RITUAL', 'INCANTATION']

'FUNC' NAME '(' [params] ')' '{' block '}'
```
defines a function with a given NAME with a list of parameters that runs a block of code

#### DEFINE TYPE
Defines the type of spell:
* SUSTAIN: a spell that doesn't end, uses X mana a second
* RITUAL: a spell that takes total concentration, typically with multiple casters. Needs to be completed to have any affect. Uses X mana a second and Y mana to complete
* INCANTATION: a spell that uses a single burst of mana to cast

# TODO Finish Grammar

# Classes

## Token
### Token.create(MATERIAL)
Uses mana to create or enchant a specific item / material. 

### Token.sacrifice(MATERIAL)
Uses mana, or in the case of gold gives mana, to empower a spell.

# Elements
Using this system there are 4 Main Elements which can be combined for a countless number of sub elements.

- Fire
- Water
- Air
- Earth
- Space

## Sub Elements

- Steam: Fire + Water


# Interacting with the world