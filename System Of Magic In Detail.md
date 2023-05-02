 Behind the scenes Magic is really just a programming language that can take in data from the world and the spell caster(s) and can output / interact with the physical world or metaphysical world.

An important note is that magic power available if finite in a given space and despite the world having a large amount of magical power, without intervention, it will run out of power eventually. 

---
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

---
# Classes

## Token
### Token.create(MATERIAL)
Uses mana to create or enchant a specific item / material. 

### Token.sacrifice(MATERIAL)
Uses mana, or in the case of gold gives mana, to empower a spell.


## Forms and Meanings
#### Wall
Creates a wall of that element(s).
IE: Earth Wall -> CombineElements([Elements.Earth]).Form(Forms.Wall).cast()

#### Projectile
Creates a projectile of that element(s).
IE: Fireball -> CombineElements([Elements.Fire]).Form(Forms.Projectile).cast()

#### Conjure
Conjures the element(s) into existence.
IE: Flame -> CombineElements([Elements.Fire]).Form(Forms.Conjure).cast()




---
# Elements
Using this system there are 4 Main Elements which can be combined for a countless number of sub elements.

- ##### Fire:
	- The power of flames and heat, useful for destruction or illumination
- ##### Water:
	- The power of oceans, rivers, and rain, useful for healing or transportation
- ##### Air:
	- The power of wind, useful for movement and communication
- ##### Earth:
	- The power of nature, useful for growth and stability
- ##### Space:
	- The power of spatial manipulation, useful for teleportation and interdimensional travel.
- ##### Time:
	- The power of temporal manipulation, useful for altering the flow of time and foreseeing future events
- ##### Light:
	- The power of radiance and clarity, useful for dispelling darkness, deception, and empowering
- ##### Darkness:
	- The power of shadows and mystery, useful for stealth and subterfuge

## Sub Elements

- Steam: 
	- Fire + Water
- Energy: 
	- Light + Air + Space
- Spirit: 
	- Light + Time
- Life: 
	- Water + Earth


---

# Interacting with the world