# Java Battle Simulator

## Overview
A text-based RPG battle simulator built in Java for an Object-Oriented 
Programming course at Drake University. The player selects a character 
and weapon, then battles through three increasingly difficult monster 
encounters with stat upgrades between rounds.

## Gameplay
- Choose from three playable characters: Elf, Wizard, or Barbarian
- Each character has unique stats, a special ability, and different 
  weapon options (e.g. a Wizard chooses between potions and a wand)
- Battle through three levels of monsters, with one round of stat 
  upgrades between each victory
- Win by defeating all three monsters, or get a game over and try again

## OOP Concepts Demonstrated
- **Inheritance** — Character and weapon subclasses inherit from base 
  classes, avoiding repeated code across similar objects
- **Encapsulation** — Character and weapon logic grouped into dedicated 
  classes
- **Polymorphism** — Overridden dealDamage methods allow characters to 
  attack and take damage in unique ways
- **Interfaces** — Two interfaces implemented for extensibility
- **Data Hiding** — Private, public, and protected access modifiers used 
  throughout

## Technologies
- Java
- JUnit

## Usage
Clone the repository and compile the Java files:

```bash
git clone https://github.com/YOUR-REPO-HERE
cd Battle-Simulator
javac *.java
java Main
```
