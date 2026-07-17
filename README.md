# C++ Practice

A personal repository to keep track of my daily C++ progress. I'm currently doing a mandatory summer internship during the day, so my goal is to consistently write code every evening to build a solid programming foundation.

## Day 1: Syntax refresh and basics

Spent some time today reviewing the core mechanics of C++ to get my muscle memory back. Wrote a few simple console programs to test the logic:

- Variables & I/O: Practiced handling basic data types and standard input/output.
- Conditional statements: Set up a simple grade evaluation program using if-else logic.
- Loops: Implemented the standard FizzBuzz algorithm.
- Nested loops: Created a basic star pattern generator in the console.

Trying to keep it simple and stay consistent.

## Day 2: Functions, Arrays, and Layout Logic

Continued the review by moving into more structured data types and code organization. Wrote 6 different programs to cover functions, memory references, and basic multidimensional structures.

What I did today:
- Functions & Overloading: Practiced basic function definitions and implemented function overloading to calculate areas for different geometric shapes (square, rectangle, triangle).
- Arrays & Data Analysis: Built a basic program to store grades in an array, calculate the average, and find the maximum value.
- References & Parameters: Implemented a swap function using memory references (`&`) and experimented with default parameters for tax calculations.
- 2D Arrays (Matrices): Created a 3x3 matrix and wrote code to calculate the sum of its main diagonal elements.
- String Manipulation: Used built-in string methods like `.length()`, `.substr()`, and `.find()` to filter and analyze text data.

## Day 3: Pointers and Dynamic Memory

Shifted focus toward how C++ handles memory directly. Moved from static stack memory to heap allocation and pointer manipulation.

What I did today:
- Pointer Arithmetic: Accessed and printed array elements directly using pointer notation `*(notlar + i)` instead of standard indexing.
- Dynamic Memory Allocation: Used the `new` operator to allocate an array size determined at runtime by user input.
- Memory Cleanup: Practiced proper memory management by using `delete[]` to free dynamic allocations and resetting pointers to `nullptr` to avoid leaks.

 ## Day 4: Structures and Object-Oriented Programming (OOP)

Introduced custom data structures and the fundamentals of Object-Oriented Programming, focusing on data encapsulation, classes, and member protection.

What I did today:
- Structures (Struct): Created a custom structure to group related attributes (title, author, page count) and managed an array of structures using standard I/O operations.
- Classes & Encapsulation: Built a class with private data members to secure data from direct external access.
- Constructors & Methods: Practiced initializing object instances using class constructors and defining public member functions to display state.

## Day 5: OOP Inheritance and Method Overriding

Explored core Object-Oriented Programming concepts further by focusing on class relationships, code reusability, and behavior modification.

What I did today:
- Inheritance: Created a base class (`Hayvan`) and a derived class (`Kopek`) to implement hierarchical relationships.
- Access Specifiers: Explored the `protected` keyword to allow derived classes access to base class member variables while keeping them hidden from the outside.
- Constructor Delegation: Practiced initializing base class attributes from a derived class constructor using initialization lists.
- Method Overriding: Implemented method overriding by redefining base class behaviors in the derived class to change execution outputs.

## Day 6: Conceptualizing Linked Lists

Focused entirely on understanding foundational data structures today, specifically Singly Linked Lists, without running new code. Analyzed how data points connect dynamically in memory.

What I studied today:
- Node Design: Looked at how a `struct` can combine a data variable with a pointer referencing the next element.
- Pointer Linking: Reviewed the mechanism of chaining isolated memory allocations together sequentially using pointers.
- Traversal Logic: Analyzed how a temporary pointer moves through a chain inside a `while` loop until it encounters `nullptr`.
- Manual Cleanup: Reviewed the process of explicitly deallocating each individual node from the heap to prevent memory leaks.

## Day 7: Linked List Manipulation - Prepending Nodes

Moved from theoretical structure design to practical implementation by actively modifying a Singly Linked List configuration at runtime.

What I did today:
- Prepending Logic: Successfully implemented node insertion at the beginning of a linked list by rerouting pointer addresses.
- Head Pointer Reassignment: Tracked the original starting node while safely shifting the main list entry pointer to the newly created front node.
- Structural Traversal: Iterated through the dynamically extended structure to verify the custom insertion order sequentially.
- Memory Deallocation: Explicitly freed all dynamic heap memory allocated for both the initial structure and the new front element.

  ## Day 8: Linked Lists - Appending & Deletion

Expanded linked list operations by adding more manipulation features.
- Implemented appending logic to add a new node to the end of the list.
- Created a search and delete mechanism to remove a specific node by its value.
- Practiced updating pointer connections and freeing memory after structural changes.

  ## Day 9: Stacks (LIFO) & STL Stack

Explored the Stack data structure and compared manual implementation with C++ Standard Template Library (STL).
- Built a custom Stack from scratch using linked list nodes with manual `push` and `pop` functions.
- Re-implemented the same logic using the built-in `<stack>` container to understand STL abstraction.
- Practiced LIFO (Last In, First Out) operations and proper memory management during stack deletions.

  ## Day 10: Queues (FIFO)

Explored the Queue data structure and its implementation using dynamic allocation.
- Built a custom Queue from scratch using linked list nodes with `enqueue` and `dequeue` functions.
- Managed separate head (`ilk`) and tail (`son`) pointers to achieve efficient operations.
- Handled edge cases like empty tracking and proper memory clearing during deletions.

  ## Day 11: Recursion 

Explored functions that call themselves to break down complex problems into smaller sub-problems.
- Implemented a recursive summation function to calculate cumulative sums.
- Developed a recursive Fibonacci sequence generator to analyze mathematical progressions.
- Explored recursive call stacks and analyzed the performance/computational limits of basic recursive algorithms.

  ## Day 12: Sorting Algorithms & STL

Explored algorithmic sorting techniques, comparing manual implementation with the C++ Standard Template Library (STL).
- Built a custom Bubble Sort algorithm from scratch to understand nested loops, array traversal, and element swapping mechanics.
- Implemented `std::sort` from the `<algorithm>` library for highly optimized, production-level sorting.
- Used `<functional>` (`std::greater<int>()`) to modify the default sorting behavior and understand basic functional objects.
