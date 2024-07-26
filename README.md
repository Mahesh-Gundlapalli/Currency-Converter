# Sorting_Visualizer
Implementation of Sorting Algorithms Visualization using C++ and SDL2 Library.

A sorting algorithm is a procedure applied to arrange the elements in a given list in a particular order. Many algorithms exist for the process of sorting, but only a few out of these are applicable in practice due to their time and space efficiency. In this assignment, we are going to be implementing an SDL2 Library-based sorting visualizer in C++. It will help us in understanding how some of the crucial sorting algorithms work by providing a view of the whole sorting process.

Our sorting visualiser is going to illustrate the working of the following sorting algorithms :

1. Selection Sort  
2. Insertion Sort  
3. Bubble Sort  
4. Merge Sort  
5. Quick Sort  
6. Heap Sort  

The visualiser is going to use a fixed list size of 130 elements. There will be options for the user to randomise the list and select any of the above-mentioned sorting algorithms for implementation. Each algorithm will carry out the sorting in non-decreasing order.

It's worth noting that this project's visualization for the sorting times doesn't represent the real time complexities of these algorithms. Particularly, intentional delays have been introduced in this visualization so that even quicker algorithms like Merge Sort are more appropriately visualized. This will make it easier for a user to view and understand the sort execution for each algorithm involved, even for those at higher speeds.

This is a sorting algorithms visualizer, so it should be able to show more regarding the functions of various sorting algorithms and what makes them superior or inferior compared to each other in terms of efficiency and complexity.



## How to Run

#### Option 1: Run from the Release

1. **Download the Release:**
   - Obtain the release version of Sorting Visualizer.

2. **Run the Application:**
   - Execute the `Sorting Visualizer.exe` file.

#### Option 2: Run from the Source Code

1. **Download the Source Code:**
   - Obtain the `Sorting Visualizer.cpp` file from the repository.

2. **Setup SDL2 Library:**
   - You will need to install and set up the SDL2 library.
   - Follow the Lazy Foo' Productions' tutorial for guidance.
   - **Important Note:** The tutorial covers setting up the 32-bit library. For Sorting Visualizer, you need the 64-bit library. Use the `x86_64-w64-mingw32` folder instead of `i686-w64-mingw32` during setup.

3. **Include the Source Code:**
   - After setting up the SDL2 library, include `Sorting Visualizer.cpp` in your project.
   - Follow the build options mentioned in the tutorial to compile and run the project.



## Usage

**Warning:** Giving repetitive commands may cause latency and the visualizer may behave unexpectedly. Please ensure that a command has finished executing before issuing a new one.

### Available Controls:

- Press `0` to generate a new randomized list.
- Press `1` to start the Selection Sort algorithm.
- Press `2` to start the Insertion Sort algorithm.
- Press `3` to start the Bubble Sort algorithm.
- Press `4` to start the Merge Sort algorithm.
- Press `5` to start the Quick Sort algorithm.
- Press `6` to start the Heap Sort algorithm.
- Press `q` to exit the Sorting Visualizer.

## Samples

![example1](https://github.com/user-attachments/assets/2bedff7c-1cb1-49ba-9a94-221dc5fa9405)

![example2](https://github.com/user-attachments/assets/b58074a6-43bb-4d1f-9879-af2276c5452f)
