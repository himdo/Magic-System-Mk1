# Description

Creates a small fire continuous fire at range 0 from caster. This spell is sustainable and uses 3 mana a second to sustain.

# Code
```
DEFINE TYPE SUSTAIN

FUNC Main () {
  CombineElements([Elements.Fire]).Form(Forms.Conjure).cast()
}
```


# Use Cases
* Burn / ignite item
* Create small light
* Create small heat source