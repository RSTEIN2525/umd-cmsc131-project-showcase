# Project #9: Recursion Exercise

**Overview:**  
This project focuses on implementing recursive methods to process strings and arrays, highlighting the power of recursion and preparing for recursion-heavy concepts in CMSC132 and the final exam.

---

## Objectives
- Develop proficiency in writing **recursive methods**.
- Avoid using iterative constructs (e.g., `for`, `while`).
- Process data such as strings and 2D arrays recursively.
- Gain deeper insight into recursion as a problem-solving technique.

---

## Features

### Recursive Methods
Implemented the following recursive methods in the `Utilities` class:
1. **String Processing**:
   - Recursive operations on strings such as replacements and substring manipulations.
2. **Array Operations**:
   - Recursive navigation and modification of 1D and 2D arrays.
   - Replacing specific cells in a 2D array using recursive calls to traverse its rows and columns.

### Key Highlights
- **No Loops**: Entire implementation avoids constructs like `for`, `while`, and `do-while`.
- **Auxiliary Methods**:
  - Private helper methods were utilized to simplify recursion logic and support modularity.
- **Modeling 2D Arrays**:
  - Visualized arrays as rows and columns to avoid coordinate-switching errors during recursive traversal.
- **Edge Case Handling**:
  - Properly handled boundary conditions and base cases to prevent infinite recursion.

---

## Challenges & Solutions
- **Challenge**: Avoiding iteration entirely in complex operations like 2D array traversal.  
  **Solution**: Designed efficient base cases and recursive logic to replace cells or process array elements row-by-row.
  
- **Challenge**: Debugging stack overflow errors in deep recursion.  
  **Solution**: Used small test cases (e.g., 2x3 arrays) to ensure the recursion logic was correct before scaling to larger inputs.

---

## Testing
- **Student Tests**:
  - Comprehensive test cases were written in `StudentTests.java` to validate the functionality of each method.
  - Small arrays and edge cases were used to debug recursive traversal and ensure correctness.
- **Release Tests**:
  - Successfully passed all **release tests** with a score of **100/100**.

---

## Sample Output
### Example: Replace Cells in a 2D Array
Given the following 2D array:

| Row/Col | 0    | 1    | 2    |
|---------|-------|-------|-------|
| **0**   | A    | B    | C    |
| **1**   | D    | E    | F    |
| **2**   | G    | H    | I    |

Calling the recursive `replaceCells` method with specific parameters resulted in the expected modifications, traversing each cell in a row/column order recursively.

---

## Key Takeaways
- **Understanding Recursive Design**:
  - Learned to break down problems into smaller subproblems that are solvable via recursion.
- **Improved Debugging Skills**:
  - Developed strategies to debug stack traces and visualize recursive calls.
- **Preparation for Advanced Concepts**:
  - This project reinforced concepts critical for success in **CMSC132** and future programming tasks.

---

## Tools & Technologies
- **Programming Language**: Java
- **Testing Framework**: JUnit
- **IDE**: Eclipse
  
