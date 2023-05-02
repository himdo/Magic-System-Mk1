# Description

A spell that heals the targets of their wounds. This spell heals only a set amount of damage each time it is cast and will never heal major damage like missing limbs.

# Code
```
DEFINE TYPE INCANTATION

FUNC Main () {
    CombineElements([Elements.Water, Elements.Earth]).Form(Forms.Conjure).cast()
}
```


# Use Cases
* Healing minor wounds like cuts / small gashes
