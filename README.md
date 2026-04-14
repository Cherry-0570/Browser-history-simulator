# Browser History Simulator (C++)

## Description
The Browser History Simulator is a console-based application developed in C++ that replicates the fundamental behavior of a web browser’s navigation system. It uses the stack data structure (LIFO principle) to manage browsing history efficiently.

The application allows users to visit new web pages, navigate backward and forward through previously visited pages, display the current page, view the browsing history, and clear stored history. This project demonstrates the practical application of data structures in real-world scenarios.

---

## Objectives
- To implement the stack data structure in C++
- To simulate browser navigation features such as Back and Forward
- To enhance problem-solving and programming skills
- To design a menu-driven console application
- To understand real-world applications of data structures

---

## Features
- Visit new web pages  
- Navigate backward and forward  
- Display the current page  
- Show full browsing history  
- Clear browsing history  

---

## System Architecture
The system follows a layered architecture consisting of:

1. User Interface Layer – Handles user input and output through a console-based menu  
2. Application Logic Layer – Processes user commands and controls program flow  
3. Data Structure Layer – Uses stacks to manage browsing history  

---

## Algorithm (Summary)
1. Initialize backStack, forwardStack, and currentPage  
2. Display menu and accept user input  
3. Perform operations based on user choice:
   - Visit: Push currentPage to backStack and clear forwardStack  
   - Back: Move currentPage to forwardStack and update from backStack  
   - Forward: Move currentPage to backStack and update from forwardStack  
   - Clear: Empty both stacks  
4. Repeat until the user exits  

---

## Technologies Used
- Programming Language: C++  
- Concepts: Stack, Data Structures, Algorithms  

---

## How to Run
1. Copy the code into a C++ compiler (GCC, CodeBlocks, or any online compiler)  
2. Compile and run the program  
3. Follow the menu options displayed in the console  

---

## Future Enhancements
- Implementation of a graphical user interface (GUI)  
- Integration with system browser to open URLs  
- Persistent history storage using files  
- Implementation using linked lists or doubly linked lists  

---

## Conclusion
This project demonstrates the use of stacks in simulating browser history navigation. It provides a clear understanding of how data structures can be applied to solve practical problems in software development.
