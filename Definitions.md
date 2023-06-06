### Mana
The amount of magical power possessed solely by a single person. Mana is stored in the human body in a small organ located near the kidney, which can grow to hold more mana as the caster gets more experience. This organ is extremely rare and is considered a mutation. It can be transplanted but with extremely low chance of survival form either parties. The name of the organ is Incantorium.
 
### Total Spell Power
The total amount of magical power that a single spell can use, can be calculated by adding the caster(s) [[#Mana]] and the amount of [[#Sacrificial Gold]]. In addition to this the casters mood plays a small role in spell power, the more sad / hurt (mentally) the power goes up and someone who is happier has slightly less spell power.

### Sacrificial Gold
Sacrificial Gold is gold that is designated to be destroyed by a given spell to achieve higher spell power. The amount of surface area determines how fast the gold is resolved into energy, where the more surface area the gold will resolve more rapidly creating mana. Gold with small surface area acts more like a trickle of mana where as if it has large amounts it acts more like a capacitor and releases mana faster. However you will have to be careful with how rapidly you extract mana out of gold, too rapidly and you will make a mana bomb. Sacrificial Gold is not common knowledge and is only known by a handful of casters.

### Mana Bomb
A mana bomb is an explosive that occurs from any device that stores mana, including the human body. The size of the explosion is directly related to the amount of mana that is released and relates similarly to the power of the different spell tiers. The most common reason for a mana bomb explosion to occur is when a form of mana storage device gets overcharge or charges to rapidly. A mana bomb made from a human body is typically very small, for the most part only killing the user. But in a user with a very large Incantorium can become a larger mana bomb.

### Spell Tier
Every spell can be ranked into a spell tier. This tier is used as a way to determine the range of [[#Total Spell Power]] required to complete a spell. Each tier requires exponentially more power to cast, however within a given tier the spell cost is fairly linear and only vary by a small amount. There is no limit to the amount of tiers, but there are a couple of important tiers:

- Tier 0: In this tier, most people who contain [[#Mana]] **can cast** these spells without any other help.
- Tier 1: In this tier, most people who contain [[#Mana]] **can not cast** these spells on their own and either require multiple [[#Casters]] to cast or need [[#Sacrificial Gold]] to augment their power.
- Tier $\infty$: These are spells that only end when it expends the [[#Casters]] [[#Total Spell Power]] or is interrupted in some way.


### Spell
TODO

### Casters
A person who can use magic to casts spells.

### Magic
Magic can be defined as a system that utilizes different techniques to affect changes in both the physical and metaphysical world.

It achieves this by manipulating various states and energies in the world, which results in extraordinary phenomena that can go beyond the limits of natural laws.


# Mana required per spell level

$$
f(x) =
\begin{cases}
l(n,x)+(t(n,m)-l(n,m)) & \text{if } 0 \leq x < m \\
t(n,x) & \text{if } m \leq x < 1
\end{cases}
$$

$$l(l_n,x) = log(x+1.5)^.25$$
$$t(t_n,x)=(n*x)^{n+2}$$
$$m=.5$$
$$n=tier level$$


#### Note
This is still heavily work in progress and will change in the future.



