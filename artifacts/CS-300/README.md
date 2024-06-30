# CS 300 Artifact: Academic Advising Application with Hash Table Implementation

## Overview
This artifact showcases a robust academic advising application developed for the CS 300 course, enhanced with a hash table implementation. The application efficiently manages course data crucial for academic advisors at ABCU, ensuring quick access and manipulation of essential information.

## Enhancement Category: Algorithms and Data Structures

### Description
The application employs a hash table to store comprehensive course details, including course numbers, titles, and prerequisites. This choice optimizes search, insert, and delete operations, essential for environments demanding rapid data retrieval.

### Objectives
- **Optimize Data Retrieval:** Utilize a hash table for swift and efficient data operations.
- **Enhance Scalability and Performance:** Ensure the application handles expanding datasets without compromising performance.
- **Support Complex Data Interactions:** Enable advanced search functionalities and streamline data management.

### Key Functionalities
- **Hash Table for Data Management:** Implements a hash table with linked lists to manage collisions effectively, ensuring efficient data handling under varying workloads.
- **Dynamic Data Insertion and Retrieval:** Facilitates real-time course searches and seamless addition of new course data.
- **Comprehensive Course Management:** Supports operations such as listing all courses and retrieving detailed course information.

### Code Review and Optimizations
The backend structure of the application includes:
- **Custom Hash Function:** Uses modulo operation (`key % tableSize`) to determine hash indices, minimizing collisions and evenly distributing data across the hash table.
- **Collision Handling:** Employs chaining via linked lists to resolve collisions, allowing multiple courses with identical hash keys to coexist at the same index.
- **Insert Function:** Ensures uniqueness by checking for duplicates before insertion, appending new nodes to the appropriate index in case of collisions.
- **Search and Print Functions:** Enables efficient course retrieval and organized printing of course details, showcasing the hash table's efficiency in data retrieval.

### Enhancements
- **Improved Search Efficiency:** Optimized hash function and collision handling significantly boost search speeds.
- **User Interface Enhancements:** Intuitive command-line interface with clear prompts enhances user interaction and data management efficiency.

### Reflections
- **Challenges:** Implementing effective collision handling mechanisms challenged efficient access as the dataset expanded.
- **Learning Outcomes:** Enhanced understanding of hash tables' practical application and their critical role in optimizing software performance.
  
## Conclusion
This artifact exemplifies my capability to implement and optimize complex data structures, enhancing software functionality and performance. It underscores my growth in software development and readiness to tackle advanced data management challenges in real-world applications.
