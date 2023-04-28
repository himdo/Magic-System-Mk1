### Mana
The amount of magical power possessed solely by a single person.
 
### Total Spell Power
The total amount of magical power that a single spell can use, can be calculated by adding the caster(s) [[#Mana]] and the amount of [[#Sacrificial Gold]].

### Sacrificial Gold
Sacrificial Gold is gold that is designated to be destroyed by a given spell to achieve higher spell power. Sacrificial Gold is not common knowledge and is only known by a handful of casters.

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



