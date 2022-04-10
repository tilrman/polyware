# Polyware
Generate passphrases using polyhedral dice

## Introduction

Arnold G. Reinhold's Diceware (https://theworld.com/~reinhold/diceware.html) uses five six-sided dice to generate one word of 
a passphrase. Polyware uses polyhedral dice to generate an entire 
fantastical sentence!

## Example
The lovely halfling warlock impales the gruesome devourer.

## Mechanic
Roll a standard set of polyhedral dice: d4, d6, d8, d12, d20, and d100. 
Look up each die roll in the corresponding word list to find the random 
word. Then assemble the words according to the following template, 
Mad-Libs style:

The [d6] [d4] [d12] [d20] the [d8] [d100].

Each sentence produces about 22.1 bits of entropy. 

## Template

The [adjective] [racial] [class] [verb] the [monster_adjective] [monster].

## Word Lists
```
[adjective]
  1 cheeky
  2 daring
  3 heroic
  4 lovely
  5 plucky
  6 strong

[racial]
  1 dwarvish
  2 elvish
  3 gnomish
  4 halfling

[class]
  1 barbarian
  2 bard
  3 cleric
  4 druid
  5 fighter
  6 monk
  7 paladin
  8 ranger
  9 rogue
 10 sorcerer
 11 wizard
 12 warlock

[verb]
  1 attacks
  2 burns
  3 crushes
  4 defeats
  5 eviscerates
  6 flays
  7 guts
  8 hacks
  9 impales
 10 jabs
 11 kills
 12 loots
 13 mutilates
 14 nicks
 15 obliterates
 16 pierces
 17 resists
 18 stabs
 19 tears
 20 whacks

[monster_adjective]
  1 dreadful
  2 enormous
  3 gruesome
  4 horrible
  5 ruthless
  6 sinister
  7 terrible
  8 vomitous

[monster]
 00 archon
 01 baboon
 02 badger
 03 barghest
 04 basilisk
 05 bear
 06 boar
 07 bugbear
 08 camel
 09 centaur
 10 cheetah
 11 chimera
 12 choker
 13 cockatrice
 14 crocodile
 15 delver
 16 devil
 17 devourer
 18 digester
 19 dinosaur
 20 djinni
 21 donkey
 22 dragon
 23 drow
 24 dryad
 25 eagle
 26 elephant
 27 ettercap
 28 ettin
 29 fungus
 30 gargoyle
 31 ghost
 32 ghoul
 33 giant
 34 goblin
 35 golem
 36 gorgon
 37 griffon
 38 grig
 39 hag
 40 harpy
 41 hawk
 42 hippogriff
 43 hobgoblin
 44 homunculus
 45 horse
 46 howler
 47 hydra
 48 hyena
 49 imp
 50 kobold
 51 kraken
 52 lamia
 53 leopard
 54 lich
 55 lion
 56 lizard
 57 manticore
 58 medusa
 59 mimic
 60 mummy
 61 naga
 62 nixie
 63 nymph
 64 octopus
 65 ogre
 66 ooze
 67 orc
 68 owlbear
 69 pegasus
 70 pixie
 71 porpoise
 72 rakshasa
 73 raven
 74 rhinoceros
 75 roc
 76 roper
 77 salamander
 78 satyr
 79 shadow
 80 shrieker
 81 skeleton
 82 snake
 83 sphinx
 84 squid
 85 succubus
 86 tiger
 87 titan
 88 triton
 89 troll
 90 unicorn
 91 vampire
 92 weasel
 93 werewolf
 94 wight
 95 wolf
 96 wolverine
 97 wraith
 98 wyvern
 99 zombie
```
