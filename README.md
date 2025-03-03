# MarioSort 🍄

A Super Mario-themed GUI application for visualizing and comparing various sorting algorithms. 📊

## Description

MarioSort is a C++ project that uses SFML to create an interactive, visually engaging experience for learning about sorting algorithms. 🎮 Inspired by the Super Mario universe, this application allows users to:

* Input a list of numbers. 🔢
* Select from a variety of sorting algorithms (Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, Radix Sort, and Heap Sort). 🧮
* Visualize the sorting process with animated bars. 📊
* Choose the sorting order (Ascending or Descending). ⬆️⬇️
* Choose the animation speed. ⏩⏪
* Hear Super Mario themed sound effects during sorting. 🔊
* Enjoy a Super Mario themed GUI. 🍄

This project is intended for educational purposes, providing a fun and intuitive way to understand how different sorting algorithms work. 💡

## Features

* **Interactive GUI:** Built with SFML, providing a smooth and responsive user interface. 🖱️
* **Multiple Sorting Algorithms:** Implements and visualizes several common sorting algorithms. 🧮
* **Customizable Visualization:** Users can control the sorting order and animation speed. 🎮
* **Super Mario Theme:** Includes Super Mario-themed fonts, sound effects, and background. 🍄
* **User-Friendly Input:** Easy input of numbers for sorting. 🔢

## Dependencies

* SFML (Simple and Fast Multimedia Library)
* C++17 or higher compiler.

## How to Build and Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/MarioSort.git](https://github.com/YourUsername/MarioSort.git)
    cd MarioSort
    ```
2.  **Ensure SFML is installed:** Follow the SFML installation instructions for your operating system.
3.  **Compile the code:**
    * Using a C++ compiler (e.g., g++), compile the `main.cpp` file along with the necessary SFML libraries. Example using g++:
        ```bash
        g++ main.cpp AlgosHeader.h CustomVector.h -o MarioSort -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
        ```
    * If you are using Visual Studio, open the .sln file, and build the project.
4.  **Run the executable:**
    ```bash
    ./MarioSort
    ```
    Or run the .exe file that was created.
5.  **Place the assets:** Place the SuperMario256.ttf, brown-brick-wall-texture-wall-bricks_146714-3037.png, maro-jump-sound-effect_1.wav and untitled_3.wav files in the same directory as the executable.

## Usage

1.  Enter up to 15 numbers separated by spaces in the input prompt.
2.  Select a sorting algorithm from the menu.
3.  Choose the sorting order (ascending or descending).
4.  Select the animation speed.
5.  Observe the sorting process visually and listen to the sound effects.
6.  Restart or exit the application.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request. 

