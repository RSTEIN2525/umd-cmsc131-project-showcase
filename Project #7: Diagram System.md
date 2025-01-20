# Project #7: Diagram System

**Overview:**  
Developed a `Diagram System` to support creation, display, and animation of two-dimensional diagrams using Java. This project focused on advanced concepts like two-dimensional arrays, interfaces, and graphical utilities for animations.

---

## Features

### **Core Classes and Utilities**
1. **`TwoDimArrayUtil`**:
   - **Key Methods**:
     - `isRagged(char[][] array)`: Checks if a 2D array has uneven row lengths.
     - `rotateTopOneRow(char[][] array)`: Rotates the top row of a 2D array.
     - `rotateLeftOneColumn(char[][] array)`: Rotates the left column of a 2D array.
     - `appendTopBottom(char[][] array1, char[][] array2)`: Combines two arrays vertically.
     - `appendLeftRight(char[][] array1, char[][] array2)`: Combines two arrays horizontally.

2. **Diagram Classes**:
   - **`HorizontalBars`** and **`VerticalBars`**:
     - Generate diagrams with dynamic animation for horizontal or vertical bars.
   - **`Flag`**:
     - Creates customizable flag diagrams with user-defined dimensions and colors.
   - **`CombineLeftRight`** and **`CombineTopBottom`**:
     - Combine multiple diagrams into a single display.

### **Graphical Features**
- Used **GraphicalUtilities** to:
  - Render diagrams dynamically.
  - Animate diagrams step-by-step for smooth transitions.
- All diagrams work seamlessly with the graphical system once the backend logic is implemented.

---

## Key Functionalities
- **Diagram Manipulation**: Rotate rows/columns, append arrays, and combine diagrams horizontally/vertically.
- **Animations**: Created smooth transitions for diagrams like horizontal and vertical bars.
- **Reusable Code**: Modularized utilities for scalability and efficient debugging.

---

## Key Learnings
- **Two-Dimensional Arrays**: Mastered operations like rotations, appending, and transformations.
- **Interface Design**: Implemented modular, reusable classes adhering to Java's interface standards.
- **Graphical Integration**: Successfully linked backend logic with graphical utilities for real-time diagram rendering.
- **Testing and Debugging**: Developed comprehensive student tests to validate methods before release.

---

## Technologies Used
- **Programming Language**: Java  
- **Utilities**: GraphicalUtilities for rendering and animations  
- **Testing Framework**: JUnit

---

## Sample Output

**Driver Example Output**:
```
Original:
[A, B]
[C, D]
[E, F]
After one top rotation:
[C, D]
[E, F]
[A, B]
After two top rotations:
[E, F]
[A, B]
[C, D]
After left rotation:
[F, E]
[B, A]
[D, C]
After left right append:
[G, H, M, N]
[I, J, O, P]
[K, L, Q, R]
After top bottom append:
[G, H]
[I, J]
[K, L]
[M, N]
[O, P]
[Q, R]
Animation of horizontal bars:
Original:
[R, R, R, R, R, R]
[R, R, R, R, R, R]
[G, G, G, G, G, G]
[G, G, G, G, G, G]
[B, B, B, B, B, B]
[B, B, B, B, B, B]

Animation Step: 1
[R, R, R, R, R, R]
[G, G, G, G, G, G]
[G, G, G, G, G, G]
[B, B, B, B, B, B]
[B, B, B, B, B, B]
[R, R, R, R, R, R]
```

---

## Note
Due to school policy, the source code cannot be shared in this repository. For more details or code samples, please contact me directly.
