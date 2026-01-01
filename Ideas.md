# Ideas

- Refactor armor class handlin to compute *per piece* and then come back together for overall rating
- Refactor on damage event to pass attacker, victim, and cause to a function
  - spells can then call this same damage function and manually set the attacker,
  so that the attacker can be known in cases where external code can't determine the attacker
- Add command to allow players to pick their class if they don't have one
  - modify hasClass() to also search variables to check if a player has a class
  - add functions to list which classes player has
  - isValidClass() to check of a class is valid, canPlayerPickClass() to limit which classes a player can pick
- re-order name of mana and maxMana variables
- look at permission naming and other naming to clean things up

- function "pointers" for projectile system?

- make monsters more powerful

- create script to keep track of block changes?
  - provide function to determine if a block is natural or not

# Herobrine

- allow Herobrine to enter and leave spectator mode at will
- create spell to destroy all nearby leaves
- create spell to dig long 2x2 tunnel
- create spell to build pyramid
- create spell to build sphere
- create spell to summon undead knights
- create spell to summon zombie horde
- create spell to summon evokers
