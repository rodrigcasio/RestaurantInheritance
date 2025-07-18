# Restaurant Inheritance Hierarchy (C++)

This is a small C++ project I made to practice object-oriented programming (OOP), especially inheritance. The program uses a restaurant theme to show how single, multiple, and virtual inheritance work in C++.

## What does it do?

- **Creates different types of restaurants** (Mexican, Japanese, and a fusion of both) using classes and inheritance.
- **Manages menus** for each restaurant using vectors.
- **Shows how polymorphism works** by letting each restaurant describe its own cuisine.
- **Demonstrates inheritance** by having some classes inherit from more than one parent (multiple inheritance) and using virtual inheritance to avoid problems.
- **Prints out information** about each restaurant and their menus.

## Example Output

When you run the program, you’ll see output like this (screenshot or text):

![Restaurant Hierarchy Output](Screenshot2025-04-27.png)

## Why did I make this?

I wanted to get more comfortable with C++ classes, inheritance, and how to use vectors. This project helped me understand how single and multiple inheritance work, and how to use virtual inheritance to solve the diamond problem.

## How to Run

1. Make sure you have a C++ compiler (like g++) installed.
2. Compile the code:
   ```
   g++ src/mainRestaurant.cpp src/fns_*.cpp -I include -o restaurant
   ```
3. Run the program:
   ```
   ./restaurant
   ```

## Author

Rodrigo Casio  
[My GitHub Profile](https://github.com/rodrigcasio)

