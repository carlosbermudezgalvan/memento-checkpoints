# ⏳ Memento Checkpoints Game

## 🎯 Project Focus: State Management and Design Patterns

This repository presents a simple, runnable game project built in Java with the primary goal of demonstrating the **Memento Design Pattern**.

The Memento pattern is used to implement a reliable **checkpoint system**, allowing the game's originator object (the character state) to be saved and restored without exposing its internal structure.

**Key concepts demonstrated:**

1.  **State Preservation:** Saving the character's position and attributes at specific moments (checkpoints).
2.  **Encapsulation:** Ensuring the internal state of the originator remains private, with the memento object serving as a token for restoration.
3.  **Restoration:** Reverting the game state to any previously saved checkpoint.

## ⚙️ Technical Features

* Visual and playable representation of the **Memento pattern** in action.
* Implementation of the **Originator**, **Memento**, and **Caretaker** roles.
* Simple movement and checkpoint interaction logic.

##  UML Diagram

The complete design structure of the Memento pattern implementation is available in the repository:

* **File:** `UML class memento.pdf`

## 🚀 Execution

### Prerequisites

* Java Development Kit (JDK) 8 or higher.

### Steps

1.  Clone the repository.
2.  Open the project in your Java IDE.
3.  Execute the main application file:
    * `src/main/launcher.java`
4.  Interact with the game to create and restore checkpoints.

---
## Contribution & Contact

This project is part of a personal portfolio showcasing foundational software engineering skills. Contributions, technical questions, and feedback are welcome.

**Author:** Carlos Bermúdez
**Email:** carlosbermudezgalvan132@gmail.com
