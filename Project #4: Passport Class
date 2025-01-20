# Project #4: Passport Class

**Overview:**  
Designed and implemented a `Passport` class in Java to represent a person's passport, including their full name, visited countries, and formatting preferences. This project emphasized class design, object-oriented programming (OOP) principles, and test-driven development using JUnit.

## Features

- **Class Structure:**  
  - Instance variables for the first, last, and middle names.
  - A `StringBuffer` for tracking passport stamps (countries visited).
  - A customizable separator character for formatting the `toString` method output.

- **Key Methods Implemented:**  
  - **Constructors:** Default and parameterized constructors for initializing passport objects.
  - **addStamp(String country):** Adds a country to the passport stamps.
  - **getStamps():** Returns a list of countries stamped on the passport.
  - **toString():** Formats and returns the passport details as a string.
  - **setSeparator(char separator):** Allows customization of the separator character.
  - **equals(Object obj):** Checks for equality between two `Passport` objects.
  - **compareTo(Passport other):** Compares passports alphabetically by last name, first name, and middle name.
  - **normalize(Passport passport, boolean uppercase):** Returns a normalized version of the passport (all uppercase or lowercase).
  - **resetNumberOfPassportObjects() and getNumberOfPassportObjects():** Tracks and manages the total number of `Passport` instances.

## Key Learnings and Challenges

- **Object-Oriented Design:** Practiced defining and managing class attributes, constructors, and methods effectively.
- **Test-Driven Development:** Developed comprehensive student tests in `StudentTests.java` to validate functionality and handle edge cases.
- **Data Validation:** Ensured proper handling of null values and invalid inputs across methods.
- **Refactoring:** Focused on clean, concise code while avoiding duplication, adhering to Java style guidelines, and emphasizing readability.

## Technologies Used

- **Programming Language:** Java
- **Testing Framework:** JUnit

## Sample Usage

Example output from the provided `Driver` class:  
```
Smith,Claudia,I.
Roberts,John
Samplelastname,Samplefirstname,Samplemiddlename
=============
Stamps for Smith,Claudia,I.-->SpainLondon
Smith#Claudia#I.
Smith#Claudia#I. same to Smith,Claudia,I.? true
=============
Comparing
Comp1: true
Comp2: true
Comp3: true
=============
Normalizing
Normalize #1: SMITH#CLAUDIA#I.
Normalize #2: smith#claudia#i.
Normalize #3: smith,claudia,i.
Number of objects: 7
```

## Note

Due to school policy, the actual source code cannot be shared in this repository. If you'd like to see code samples or discuss this project in detail, please contact me directly.
