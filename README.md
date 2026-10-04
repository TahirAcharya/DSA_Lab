📚 Data Structures Laboratory
![C](https://img.shields.io/badge/Language-C-blue)
![Course](https://img.shields.io/badge/Course-Data%20Structures%20Laboratory-green)
![Course Code](https://img.shields.io/badge/Code-1BCSL306-orange)
![Semester](https://img.shields.io/badge/Semester-III-purple)
![Academic Year](https://img.shields.io/badge/Academic%20Year-2026--27-red)
![Scheme](https://img.shields.io/badge/Scheme-2025-blue)
![Credits](https://img.shields.io/badge/Credits-1-brightgreen)
> **Data Structures Laboratory – 1BCSL306**  
> **Semester III | Academic Year 2026–27**  
> **Department of ISE / CSE / Data Science / AIML**  
> **Acharya Institute of Technology, Bengaluru**
---
📌 About the Repository
This repository contains the programs, algorithms, implementations, sample outputs, and supporting resources for the Data Structures Laboratory (1BCSL306).
The repository follows the verified 2026–27 Course Plan and covers fundamental linear and non-linear data structures using the C programming language.
The laboratory covers
Structures
Arrays
Stack
Queue
Circular Queue
Linked Lists
Doubly Linked Lists
Binary Trees
Binary Search Trees
Graphs
Sparse Matrices
Expression Conversion
Hashing
---
🎓 Course Information
Particular	Details
Course Title	Data Structure Laboratory
Course Code	1BCSL306
Course Type	Core
Semester	III
Academic Year	2026–27
Scheme	2025
L-T-P	0:0:2
Credits	1
Programming Language	C
Department	ISE / CSE / DS / AIML
Institution	Acharya Institute of Technology
---
🎯 Course Outcomes
CO1
Demonstrate the functionality of various data structures to real-world applications.
CO2
Demonstrate the various data structure operations.
🧩 Laboratory Structure
Part	Type	No. of Experiments
PART-A	Fixed Experiments	6
PART-B	Open-Ended Experiments	6
Total		12
---
🔵 PART-A – FIXED EXPERIMENTS
🧪 Experiment 1 – Library Management System
Problem Statement
Develop a C program for managing library book records.
Define a structure `Book` with:
```text
Book_ID
Title
Author
Price
Availability Status
```
Availability Status:
```text
Available
Issued
```
Dynamically allocate memory to store the details of `N` books.
Required Functions
```c
create()
display()
search()
issueBook()
returnBook()
```
Menu
```text
1. Add Book Records
2. Display All Book Records
3. Search Book by Book ID
4. Issue a Book
5. Return a Book
6. Exit
```
Concepts Covered
Structures
Dynamic Memory Allocation
Functions
Searching
Menu-driven Programming
Application
Library Management System
---
🧪 Experiment 2 – Stack Operations
Problem Statement
Develop a menu-driven C program for operations on a Stack of Integers using an array implementation with maximum size `MAX`.
Operations
```text
1. Push an Element
2. Pop an Element
3. Check Palindrome
4. Demonstrate Overflow
5. Demonstrate Underflow
6. Display Stack
7. Exit
```
Core Principle
```text
LIFO
Last In → First Out
```
Concepts Covered
Stack
Array Implementation
Push
Pop
Overflow
Underflow
Palindrome
---
🧪 Experiment 3 – Printer Queue
Problem Statement
Develop a C program for simulating a Printer Queue using the Queue data structure.
Operations
```text
1. Add a Print Job
2. Process/Delete a Print Job
3. Display All Pending Print Jobs
4. Display Number of Print Jobs Waiting
5. Demonstrate Queue Overflow
6. Demonstrate Queue Underflow
7. Exit
```
Core Principle
```text
FIFO
First In → First Out
```
Concepts Covered
Queue
FIFO
Enqueue
Dequeue
Front
Rear
Overflow
Underflow
Application
Printer Job Scheduling
---
🧪 Experiment 4 – Infix to Postfix Expression Conversion
Problem Statement
Develop a C program for converting an Infix Expression to Postfix Expression.
The program should support:
Parenthesized expressions
Free-parenthesized expressions
Alphanumeric operands
Supported Operators
```text
+
-
*
/
%
^
```
Example
```text
Infix:
A+B*C

Postfix:
ABC*+
```
Another Example
```text
Infix:
(A+B)*C

Postfix:
AB+C*
```
Data Structure Used
Stack
Concepts Covered
Stack
Operator Precedence
Expression Conversion
Infix Notation
Postfix Notation
Alphanumeric Operands
---
🧪 Experiment 5 – Binary Tree
Problem Statement
Develop a C program to create a Binary Tree by inserting integer elements entered by the user in level order.
Required Functions
```c
createTree()
preorder()
inorder()
postorder()
```
Menu
```text
1. Create Binary Tree
2. Display Preorder Traversal
3. Display Inorder Traversal
4. Display Postorder Traversal
5. Exit
```
Tree Traversals
```text
Preorder  → Root → Left → Right

Inorder   → Left → Root → Right

Postorder → Left → Right → Root
```
Concepts Covered
Binary Tree
Dynamic Memory Allocation
Recursion
Tree Traversals
Level-order Insertion
---
🧪 Experiment 6 – Graph of Cities using DFS/BFS
Problem Statement
Develop a C program for operations on a Graph `G` of cities.
Requirements
Create an adjacency matrix representing the graph of `N` cities.
Print all nodes reachable from a given starting node.
Use DFS/BFS methods.
Traversal Methods
```text
DFS – Depth First Search

BFS – Breadth First Search
```
Concepts Covered
Graph
Vertices
Edges
Adjacency Matrix
DFS
BFS
Graph Traversal
Application
City / Network Connectivity
---
🟢 PART-B – OPEN-ENDED EXPERIMENTS
🧪 Experiment 7 – Sparse Matrix Addition
Problem Statement
Develop a C program to:
Read two sparse matrices of the same order.
Convert both into 3-Tuple representation.
Perform matrix addition.
Display the resultant matrix in:
Normal matrix form
3-Tuple form
3-Tuple Representation
```text
Row
Column
Value
```
Concepts Covered
Sparse Matrix
3-Tuple Representation
Matrix Addition
Array Representation
---
🧪 Experiment 8 – Expression Conversion Tool
Problem Statement
Develop a C-based Expression Conversion Tool using a Stack to convert arithmetic expressions from:
```text
INFIX → POSTFIX
```
Supported Input
Alphanumeric operands
Parentheses
Supported Operators
```text
+
-
*
/
%
^
```
Example
```text
Input:
A+B*C

Output:
ABC*+
```
Requirements
The tool should be tested using various valid expressions and the correctness of the conversion should be analyzed.
Concepts Covered
Stack
Expression Parsing
Operator Precedence
Infix Expression
Postfix Expression
Expression Validation
---
🧪 Experiment 9 – Circular Queue
Problem Statement
Develop a menu-driven C program for operations on a Circular Queue.
The data may be:
Integer
Floating Point
Operations
```text
1. Insert an Element
2. Delete an Element
3. Display Circular Queue
4. Demonstrate Overflow
5. Demonstrate Underflow
6. Exit
```
Concepts Covered
Circular Queue
Front
Rear
Insertion
Deletion
Overflow
Underflow
---
🧪 Experiment 10 – Doubly Linked List of Employees
Problem Statement
Develop a menu-driven C program for operations on a Doubly Linked List (DLL) of Employee Data.
Employee Fields
```text
SSN
Name
Department
Designation
Salary
Phone Number
```
Operations
```text
1. Create DLL using End Insertion
2. Display DLL
3. Count Number of Nodes
4. Insert at End
5. Delete at End
6. Insert at Front
7. Delete at Front
8. Demonstrate DLL as Double Ended Queue
9. Exit
```
Concepts Covered
Structures
Pointers
Dynamic Memory Allocation
Doubly Linked List
Forward Traversal
Backward Traversal
Insertion
Deletion
Deque
---
🧪 Experiment 11 – Binary Search Tree
Problem Statement
Develop a menu-driven C program for operations on a Binary Search Tree (BST) of integers.
Operations
```text
1. Create BST
2. Inorder Traversal
3. Preorder Traversal
4. Postorder Traversal
5. Search
6. Exit
```
BST Property
```text
Left Subtree < Root < Right Subtree
```
Required Operations
Create BST of `N` integers
Inorder Traversal
Preorder Traversal
Postorder Traversal
Search for a given element
Concepts Covered
Binary Search Tree
Recursion
Searching
Tree Traversals
Dynamic Memory Allocation
---
🧪 Experiment 12 – Employee Record Management using Hashing
Problem Statement
Develop an Employee Record Management System using Hashing.
Key
```text
Employee ID
```
Hash Function
```text
H(K) = K mod m
```
where:
```text
K = Key
m = Hash Table Size
```
Collision Resolution
```text
Linear Probing
```
Operations
```text
1. Create Hash Table
2. Insert Employee Record
3. Resolve Collision using Linear Probing
4. Search Employee by Employee ID
5. Display Hash Table
6. Display Corresponding Memory Locations
```
Concepts Covered
Hash Table
Hash Function
Collision
Linear Probing
Searching
Employee Record Management
---
📊 Complete Experiment List
No.	Part	Experiment	Major Data Structure
1	A	Library Management System	Structure
2	A	Stack Operations	Stack
3	A	Printer Queue	Queue
4	A	Infix to Postfix	Stack
5	A	Binary Tree	Binary Tree
6	A	Graph of Cities	Graph
7	B	Sparse Matrix Addition	Matrix
8	B	Expression Conversion Tool	Stack
9	B	Circular Queue	Circular Queue
10	B	Employee Doubly Linked List	DLL
11	B	Binary Search Tree	BST
12	B	Employee Record Management	Hashing
---
🧠 Data Structures Covered
```text
Structures
Arrays
Stack
Queue
Circular Queue
Singly Linked List
Doubly Linked List
Binary Tree
Binary Search Tree
Graph
Sparse Matrix
Hash Table
```
---
🌍 Real-World Applications
Data Structure	Application
Structure	Library Management
Stack	Expression Processing / Palindrome
Queue	Printer Scheduling
Binary Tree	Hierarchical Data
Graph	City / Network Connectivity
Sparse Matrix	Efficient Matrix Representation
Circular Queue	Circular Scheduling
Doubly Linked List	Employee Records / Deque
BST	Searching
Hashing	Employee Record Management
---
🎯 CO-WISE EXPERIMENT COVERAGE
CO1
Demonstrate the functionality of various data structures to real-world applications.
Examples:
Library Management
Printer Queue
Graph of Cities
Employee Record Management
E-Commerce System Prototype
Hashing-based Employee Management
CO2
Demonstrate the various data structure operations.
Operations include:
Push
Pop
Enqueue
Dequeue
Insert
Delete
Search
Traversal
Matrix Addition
Expression Conversion
Hashing
Collision Resolution
---
💻 Programming Environment
Language
```text
C
```
Compiler
```text
GCC / C Compiler
```
Supported Platforms
```text
Windows
Linux
```
Compile
```bash
gcc program.c -o program
```
Linux / macOS
```bash
./program
```
Windows
```bash
program.exe
```
---
📁 Repository Structure
```text
DSA_Lab/
│
├── README.md
│
├── PART-A/
│   │
│   ├── 01_Library_Management/
│   │   ├── library.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 02_Stack/
│   │   ├── stack.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 03_Printer_Queue/
│   │   ├── printer_queue.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 04_Infix_To_Postfix/
│   │   ├── infix_postfix.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 05_Binary_Tree/
│   │   ├── binary_tree.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   └── 06_Graph_DFS_BFS/
│       ├── graph.c
│       ├── README.md
│       └── output.txt
│
├── PART-B/
│   │
│   ├── 01_Sparse_Matrix/
│   │   ├── sparse_matrix.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 02_Expression_Conversion/
│   │   ├── expression_conversion.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 03_Circular_Queue/
│   │   ├── circular_queue.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 04_Doubly_Linked_List/
│   │   ├── dll_employee.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   ├── 05_Binary_Search_Tree/
│   │   ├── bst.c
│   │   ├── README.md
│   │   └── output.txt
│   │
│   └── 06_Hashing/
│       ├── employee_hashing.c
│       ├── README.md
│       └── output.txt
│
├── LAB_RECORD/
│   ├── Algorithms/
│   ├── Outputs/
│   ├── Viva_Questions/
│   └── Observations/
│
├── PRACTICE/
│   ├── Stack/
│   ├── Queue/
│   ├── Linked_List/
│   ├── Trees/
│   ├── Graphs/
│   └── Hashing/
│
└── RESOURCES/
    ├── Notes/
    ├── Question_Bank/
    └── Reference_Material/
```
---
📝 Standard Laboratory Record Format
Each experiment should contain:
```text
1. Experiment Number
2. Date
3. Title
4. Problem Statement
5. Objective
6. Data Structure Used
7. Algorithm
8. Pseudocode
9. Program
10. Sample Input
11. Sample Output
12. Test Cases
13. Result
14. Inference
15. Viva Questions
```
---
📊 Experiment Evaluation
Each experiment in the laboratory record is evaluated for 30 marks.
Component	Marks
Write-Up / Logic	10
Record	6
Execution of Program	10
Viva-Voce	4
Total	30
Evaluation Criteria
Write-Up / Logic – 10 Marks
Based on the logic used for implementation and the student's own inferences.
Record – 6 Marks
Based on the quality, clarity and completeness of the written procedure and code.
Execution of Program – 10 Marks
Based on whether the student can execute the program independently and successfully.
Viva-Voce – 4 Marks
Based on understanding of logic, output and related concepts.
> **Note:** Zero marks for absentees.
---
📈 CIE Assessment
CIE – 50 Marks
Lab Test – 20 Marks
Two tests are conducted after completion of:
```text
Test 1 → 50% of Experiments
Test 2 → 100% of Experiments
```
Each test is conducted for 50 marks, averaged and scaled down to 20.
Lab Test Components
```text
Viva           → 10 Marks
Write-up       → 10 Marks
Implementation → 30 Marks
```
Continuous Lab Assessment
Each experiment is evaluated using:
```text
W – Write-up
R – Record
E – Execution
V – Viva
```
CIE Distribution
```text
Lab Test                  → 20 Marks
Continuous Lab Assessment → 30 Marks
---------------------------------------
Total CIE                 → 50 Marks
```
---
📝 SEE Assessment
SEE – 50 Marks
The SEE consists of:
```text
1 Experiment from PART-A → 70% Weightage
1 Experiment from PART-B → 30% Weightage
```
The examination is conducted for 100 marks and scaled down to 50.
SEE Rubrics
Component	Weightage
Write-up	20%
Execution	60%
Viva	20%
---
📊 Overall Assessment
```text
CIE = 50 Marks
SEE = 50 Marks
----------------
TOTAL = 100 Marks
```
---
🚀 Learning Beyond Prescribed Syllabus
🛒 E-Commerce System Prototype
Students are encouraged to design and implement an E-Commerce System Prototype using linear and non-linear data structures.
Functional Areas
```text
Product Management
        ↓
Order Processing
        ↓
Customer Interaction
        ↓
Inventory Control
```
Learning Approach
Method	Percentage
Participative	0%
Experiential	50%
Problem Solving	50%
ICT Usage
```text
ALIVE for Quiz
C Compiler
Windows / Linux
```
---
📊 CO–PO–PSO Mapping
The course plan includes the CO–PO–PSO mapping for:
```text
CO1
CO2
```
RBT Levels
```text
CO1 → L3
CO2 → L4
```
---
🎯 Target and Attainment
Parameter	Value
Previous Result	90%
Current Year Target	>90%
CO1 Target	90%
CO1 Attainment	95%
CO2 Target	90%
CO2 Attainment	95%
---
🧪 Program Submission Checklist
Before submitting an experiment:
```text
☐ Problem statement understood
☐ Appropriate data structure identified + Theory 
☐ Program implemented in C
☐ Program compiled successfully
☐ Syntax errors removed
☐ Logical errors removed
☐ Menu options tested
☐ Boundary conditions tested
☐ Overflow tested where applicable
☐ Underflow tested where applicable
☐ Multiple test cases executed
☐ Output verified by instructor
☐ Result hand written
☐ Inference written
☐ Viva questions prepared(min 4)
```
---
🧠 Student Learning Workflow
```text
Understand Problem
       ↓
Identify Data Structure
       ↓
Design Algorithm
       ↓
Write C Program
       ↓
Compile
       ↓
Debug
       ↓
Test
       ↓
Analyze Output
       ↓
Document Result
       ↓
Prepare for Viva
       ↓
Apply to Real-World Problem
```
---
📚 Viva Preparation
Students should be prepared to explain:
```text
What is a data structure?

Why is a particular data structure selected?

What is the difference between Stack and Queue?

What is LIFO?

What is FIFO?

What is overflow?

What is underflow?

What is dynamic memory allocation?

What is a linked list?

What is recursion?

What are tree traversals?

What is a Binary Search Tree?

What is DFS?

What is BFS?

What is a sparse matrix?

What is a 3-tuple representation?

What is hashing?

What is a collision?

What is linear probing?

What is the difference between Infix and Postfix?
```
---
👨‍🏫 Course Information
Acharya Institute of Technology
Department of ISE / CSE / Data Science / AIML
Course
Data Structure Laboratory
Course Code
```text
1BCSL306
```
Semester
```text
III
```
Academic Year
```text
2026–27
```
Course Faculty / Contributors
Mr. Mohammed Tahir Mirji
Dr. Abdul Khadar A
Mrs. Soniya R
Mrs. Mithuna H R
Mr. Jagadish
Ms. Deeksha
Ms. Surbhi

---
⭐ Repository Objective
This repository provides a structured environment for students to:
```text
LEARN
  ↓
UNDERSTAND
  ↓
DESIGN
  ↓
IMPLEMENT
  ↓
DEBUG
  ↓
TEST
  ↓
ANALYZE
  ↓
DOCUMENT
  ↓
EXPLAIN
  ↓
APPLY
```
---
🎯 Final Learning Goals
CO1
Demonstrate the functionality of various data structures to real-world applications.
CO2
Demonstrate the various data structure operations.
---
💡 Understand the Structure. Implement the Operation. Solve the Problem.
🚀 Happy Coding!
---
Acharya Institute of Technology  
Data Structures Laboratory – 1BCSL306  
Academic Year 2026–27
