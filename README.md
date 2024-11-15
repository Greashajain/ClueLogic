# ClueLogic
This Python project is designed to help solve the Clue deduction game using logic and model checking. It represents characters, rooms, and weapons as logical symbols and uses a knowledge base to deduce what cards might be in play based on logical constraints.

## Project Structure
**Symbols:** Each character, room, and weapon is represented as a unique symbol.

**Knowledge Base:** Contains known information about the game state, such as eliminated possibilities and constraints.

**Logic Functions:** Functions are used to check the knowledge base and deduce the possible cards. 

**Sample KnowledgeBase:-**

![Screenshot from 2024-11-14 17-05-56](https://github.com/user-attachments/assets/e69ab7b4-7d48-45e4-b7c5-d062ad9a95ee)



## Symbols

This project uses the following symbols for each game element:

### Characters:

Colonel Mustard (mustard)

Professor Plum (plum)

Miss Scarlet (scarlet)

### Rooms:

Ballroom (ballroom)

Kitchen (kitchen)

Library (library)

### Weapons:

Knife (knife)

Revolver (revolver)

Wrench (wrench)

### Output

The output will indicate which elements are confirmed (YES), eliminated (NO), or undetermined (MAYBE), with confirmed results shown in green.

