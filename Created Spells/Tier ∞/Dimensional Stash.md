# Description

This spell creates a dimensional rift that allows the caster to store and retrieve items by interacting with it. The size of the rift's interior is determined by the tier level at which the spell is cast, with higher tiers allowing for larger storage capacity. Despite its external appearance, the interior of the rift is significantly larger, and can hold an amount of items beyond what could be accommodated by its outer dimensions. The caster can access the rift at will, allowing for convenient and secure storage and retrieval of items.

# Note
This spell what the [[Magical Items#Bag of Holding|Bag of Holding]] is enchanted with, however since this uses the users mana it is flexibly in size and not bound to a physical item.

Each tier of this spell that is cast becomes a unique stash which does not overlap with the previous tier, however since each tier of magic requires exponentially more energy very few people have access to multiple stashes.

# Code
```
DEFINE TYPE RITUAL

FUNC Main () {
  CombineElements([Elements.Space, Elements.Earth, Elements.Time]).Form(Forms.Conjure).cast()
}
```


# Use Cases
* Storing Items for long term storage
* Carrying heavy items without causing strain to the caster 
