# Project #8: Media Rental Manager

**Overview:**  
Developed a **Media Rental Manager** system in Java that simulates a simplified media rental service similar to Netflix. This system allows users to manage customers, movies, and music albums with functionality for searching, renting, and managing media.

---

## Features

### **Core Classes and Interfaces**
1. **`MediaRentalManager`**:
   - Implements the `MediaRentalManagerInt` interface to provide core system functionality, including:
     - Managing **customers** with **UNLIMITED** and **LIMITED** plans.
     - Tracking **media** (movies and albums) and their availability.
     - Supporting rental queues for customers (requested and rented items).

2. **Supporting Classes/Interfaces**:
   - **`Media`**:
     - Abstract base class for **Movie** and **Album**.
     - Stores common properties such as title and available copies.
   - **`Movie`**:
     - Subclass of `Media` with additional property: **rating** (e.g., PG).
   - **`Album`**:
     - Subclass of `Media` with additional properties:
       - **artist**: Name of the artist.
       - **songs**: List of songs in the album.
   - **`Customer`**:
     - Manages customer-specific data:
       - **Name, Address, Plan Type**.
       - **Queues**: Media requested and currently rented.

3. **Interfaces**:
   - Defined to enable polymorphism and ensure reusability of code.

---

## Key Functionalities
1. **Customer Management**:
   - Add, remove, and update customer details (name, address, and plan type).
   - Manage queues for media requested and currently rented.

2. **Media Management**:
   - Add, remove, and update media items (movies and albums).
   - Support for searching media based on title, rating, artist, and songs.

3. **Rental Management**:
   - Process customer requests to rent or return media.
   - Enforce **LIMITED** and **UNLIMITED** plan rules.

4. **Sorting and Searching**:
   - Sort media items using `Collections.sort`.
   - Implement flexible search functionality for media items.

---

## Design Highlights
- **Object-Oriented Design**:
  - Used inheritance to define a shared `Media` superclass for `Movie` and `Album`.
  - Employed interfaces to decouple implementation and enforce modular design.
- **ArrayList Requirement**:
  - Used two `ArrayList` objects:
    1. For managing customers.
    2. For managing media (movies and albums).
- **Polymorphism**:
  - Allowed handling of `Movie` and `Album` objects interchangeably using the `Media` type.

---

## Key Learnings
- **Design Principles**:
  - Gained experience in designing systems using interfaces and inheritance.
- **Collections and Polymorphism**:
  - Effectively utilized `ArrayList` and `Collections.sort`.
  - Learned to manage polymorphic lists and use `instanceof` for type-specific operations.
- **Project Design**:
  - Practiced balancing functionality, scalability, and simplicity in design.

---

## Technologies Used
- **Programming Language**: Java  
- **Data Structures**: ArrayList  
- **Testing Framework**: JUnit

---

## Challenges & Solutions
- **Challenge**: Designing a flexible system to accommodate both movies and albums.  
  **Solution**: Introduced a `Media` superclass to encapsulate shared attributes and behaviors, simplifying type handling.  
- **Challenge**: Enforcing queue and plan-specific restrictions.  
  **Solution**: Integrated validation logic within the `Customer` class to manage queues dynamically.


---

## Note
Due to school policy, the source code cannot be shared in this repository. For more details or code samples, please contact me directly.
