# Restaurant Inheritance Hierarchy
C++ Project demonstrating object-oriented programming (OPP) inheritance through a restaurant hierarchy. This is an educational demo to showcase my understanding of single and multiple inheritance in C++.

## Features
- **Restaurant Types**: Base `Restaurant` class with derived `MexicanRestaurant`, `JapaneseRestaurant`, and `MexicanJapaneseFusion` classes.
- **Menu Management**: `MenuItem` class with vectors for dynamic menu storage.
- **Polymorphism**: Virtual `describeCuisine()` method overridden for unique restaurant descriptions.
- **Inheritance**: Single, multiple, and virtual inheritance to model complex relationships and resolve the diamond problem.

## Purpose
Developed as part of my C++ learning journey to master OOP concepts, including:
- **Single Inheritance**: `MexicanRestaurant` and `JapaneseRestaurant` inherit from `Restaurant`.
- **Multiple Inheritance**: `MexicanJapaneseFusion` inherits from both `MexicanRestaurant` and `JapaneseRestaurant`.
- **Virtual Inheritance**: Prevents diamond problem issues.
- **Polymorphism**: Overridden `describeCuisine()` methods for each restaurant type.

## Files
- **Source Files** (`src/`):
  - `mainRestaurant.cpp`: Main program to test the hierarchy.
  - `fns_Restaurant.cpp`: Implementation for `Restaurant` class.
  - `fns_MexicanRestaurant.cpp`: Implementation for `MexicanRestaurant` class.
  - `fns_JapaneseRestaurant.cpp`: Implementation for `JapaneseRestaurant` class.
  - `fns_MexicanJapaneseFusion.cpp`: Implementation for `MexicanJapaneseFusion` class.
  - `fns_MenuItem.cpp`: Implementation for `MenuItem` class.

- **Header Files** (`include/`):
  - `h_Restaurant.hpp`: Base `Restaurant` class declaration.
  - `h_MexicanRestaurant.hpp`: `MexicanRestaurant` class declaration.
  - `h_JapaneseRestaurant.hpp`: `JapaneseRestaurant` class declaration.
  - `h_MexicanJapaneseFusion.hpp`: `MexicanJapaneseFusion` class declaration.
  - `h_MenuItem.hpp`: `MenuItem` class declaration.
 
## How to Run
```bash
g++ src/mainRestaurant.cpp src/fns_*.cpp -I include -o restaurant
./restaurant
```

## Sample Output
![Restaurant Hierarchy Output](Screenshot2025-04-27.png)

## Learning Outcomes
- Applied C++ inheritance, including virtual inheritance to resolve ambiguity.
- Implemented polymorphism with overriden methods.
- Used vectors for dynamic menu storage.
- Applied encapsulation with private memebers and public getters.

## Note
This is a learning project to demonstrate OOP concepts, not a production application. Future projects will focus on real-world applications like inventory or banking systems.

## Author
Rodrigo Casio ([View my Github profile](https://github.com/rodrigcasio))

