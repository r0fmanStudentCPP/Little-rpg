# Simple C++ RPG Battle System 

A lightweight, text-based RPG battle simulator written in C++. This project demonstrates fundamental Object-Oriented Programming (OOP) concepts by simulating a combat encounter between two characters (a Knight and a Goblin). 

It is a great foundational project for understanding how game logic, character stats, and interactions work under the hood.

## Features

* **Custom Entities:** Create characters with customizable attributes including Health Points (HP), Mana, Base Damage, and a Name.
* **Inventory System:** Characters can hold items (like "Sword", "Potion") using `std::vector`. Includes a basic inventory capacity check.
* **Combat Mechanics:** Entities can attack each other, dynamically reducing the target's HP based on the attacker's damage.
* **Health Management:** Prevents negative HP values (caps at 0).
* **Death State Validation:** Dead entities are properly flagged and cannot perform attacks.

## Concepts Demonstrated

This project serves as a practical application of core C++ mechanics:
* **Object-Oriented Programming (OOP):** Encapsulation using `class`, `private`, and `public` access modifiers.
* **Memory Management & Performance:** Using pass-by-reference (`Entity& target`) to avoid unnecessary copying of objects.
* **Standard Template Library (STL):** Utilizing `std::string` for text and `std::vector` for dynamic arrays (inventories).
* **Uniform Initialization:** Modern C++ brace initialization for clean object creation.

## How to Run

### Using a Compiler (GCC/Clang)
1. Clone this repository or download the source code.
2. Open your terminal or command prompt.
3. Navigate to the project directory.
4. Compile the code using standard C++11 (or higher):
   ```bash
   g++ main.cpp -o rpg_battle
