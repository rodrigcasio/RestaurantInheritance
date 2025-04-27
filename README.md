# Restaurant Inheritance Hierarchy
C++ Project demonstrating object-oriented programming (OPP) inheritance through a restaurant hierarchy. This is an educational demo to showcase my understanding of single and multiple inheritance in C++.

## Purpose
This project illustrates key OOP concepts, including:
- **Single Inheritance**: `MexicanRestaurant` and `JapaneseRestaurant` inherit from `Restaurant` .
- **Multiple Inheritance**: `MexicanJapaneseFusion` inherits from both `MexicanRestaurant` and `JapaneseRestaurant`.
- **Virtual Inheritance**: Prevents diamond problem issues.
- **Polymorphism**: Overriden `describeCuisine` methods for each restaurant type.

## Files
- `mainRestaurnat.cpp`: Main program to test the hierarchy.
- `h_Restaurant.hpp`, `fns_Restaurant.cpp`: Base `Restaurant` class.
- `h_MexicanRestaurant.hpp`, `fns_MexicanRestaurant.cpp` : `MexicanRestaurant` derived class.
- `h_JapaneseRestaurant.hpp` , `fns_JapaneseRestaurant.cpp`: `JapaneseRestaurant` derived class.
- `h_MexicanJapaneseFusion.hpp`, `fns_MexicanJapaneseFusion.cpp`: `MexicanJapaneseFusion` derived class.
- `h_MenuItem.hpp`, `fns_MenuItem.cpp`: `MenuItem` class for menu management.

## Sample Output


## Learning Outcomes
- Mastered C++ inheritance, including virtual inheritance to resolve ambiguity.
- Implemented polymorphism with overriden methods.
- Used vectors for dynamic menu storage (Abril 2025).
- Applied encapsulation with private memebers and public getters.

## Note
This is a learning project to demonstrate OOP concepts, not a production application. Future projects will focus on real-world applications like inventory or banking systems.

## How to Run
```bash
g++ mainRestaurant.cpp fns_Restaurant.cpp fns_MexicanRestaurant.cpp fns_JapaneseRestaurant.cpp fns_MexicanJapaneseFusion.cpp fns_MenuItem.cpp -o restaurant
./restaurant
