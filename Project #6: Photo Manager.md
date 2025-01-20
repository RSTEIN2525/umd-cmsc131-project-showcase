# Project #6: Photo Manager

**Overview:**  
Implemented the `Photo` and `PhotoManager` classes to create a photo management application. This project emphasized advanced class design, ArrayList manipulation, and the use of the Java `Collections` class for sorting.

## Features

- **Photo Class:**  
  - Represents individual photos with attributes such as file path, dimensions, timestamp, and comments.
  - Provides methods for adding and retrieving comments, comparing photos, and generating string representations.

- **PhotoManager Class:**  
  - Manages a collection of `Photo` objects using an `ArrayList`.
  - Implements methods for adding photos, sorting by date, retrieving comments, and generating HTML pages to display photo information.

- **Key Functionalities:**  
  - **Add Photo:** Adds photos to the manager with attributes like dimensions and timestamps.
  - **Add and Retrieve Comments:** Supports adding multiple comments to a photo and retrieving them in a formatted string.
  - **Sort Photos:** Uses the `Collections` class to sort photos by date.
  - **Generate HTML Pages:** Dynamically creates HTML pages displaying photos and their metadata.

## Key Learnings and Challenges

- **Class Collaboration:** Designed classes that interact seamlessly while maintaining clear separation of responsibilities.
- **ArrayList Manipulation:** Practiced dynamic data handling with efficient storage, retrieval, and sorting of photo objects.
- **File Handling:** Gained experience in creating and managing HTML files programmatically.
- **Testing with JUnit:** Developed student tests to validate methods for both `Photo` and `PhotoManager` classes.

## Technologies Used

- **Programming Language:** Java
- **Data Structures:** ArrayList
- **Utilities:** Java Collections for sorting
- **Testing Framework:** JUnit

## Sample Output

**Driver Example Output:**  
```
PhotoManager
umcp/college1.jpg,300,400,09/17/2020-17:10
umcp/college3.jpg,200,200,11/18/2019-09:00
umcp/college8.jpg,200,200,10/18/2020-18:30

Retrieving comments for umcp/college1.jpg
School Visit,Cousins with me
After sorting photos by date
umcp/college3.jpg,200,200,11/18/2019-09:00
umcp/college1.jpg,300,400,09/17/2020-17:10
umcp/college8.jpg,200,200,10/18/2020-18:30
```

## Note

Due to school policy, the actual source code cannot be shared in this repository. If you'd like to see code samples or discuss this project in detail, please contact me directly.
