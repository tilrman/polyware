# Polyware
Generate passphrases using polyhedral dice

## Introduction
Douglas Muth's Diceware uses five six-sided dice to generate one word of a passphrase. Polyware uses polyhedral dice to generate an entire fantastical sentence!

## Example
The brave dwarven cleric stabs the evil goblin.

## Mechanic
Roll a standard set of polyhedral dice: d4, d6, d8, d12, d20, and d100. Look up each die roll in the corresponding word list to find the random word. Then assemble the words according to the following template, Mad-Lib style:

The [d6] [d8] [d12] [d20] the [d4] [d100].

Each sentence produces about 22.1 bits of entropy.
