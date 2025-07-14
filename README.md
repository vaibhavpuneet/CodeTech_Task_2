Name:Aditya kumar Company:CODETECH IT SOLUTION ID:CT04DF2936 Domain:C LANGUAGE Duration:11 JUNE 2025 TO 11 JULY 2025 Mentor:NEELA SANTHOSH KUMAR Internship Report: Linked List Implementation in C Language Introduction During my internship, I worked on implementing Linked Lists in C language, which is a fundamental data structure used for efficient memory management and dynamic data handling in programming. This helped me understand pointers, dynamic memory allocation, and node-based data structures practically.

Objective To implement a Singly Linked List in C language.

To perform Insertion, Deletion, and Traversal operations.

To understand dynamic memory allocation using malloc() and free().

To strengthen problem-solving and logical thinking for data structures.

What is a Linked List? A Linked List is a linear data structure where each element (node) contains:

Data: The value to store.

Pointer: Address of the next node in the list.

Unlike arrays, linked lists do not require contiguous memory and allow easy insertion and deletion.

Tools and Environment Language: C

Compiler: GCC (Code::Blocks/Visual Studio Code)

Operating System: Windows/Linux

Implementation Details 1️⃣ Node Structure Each node contains:

An integer data.

A pointer next pointing to the next node.

c Copy Edit struct Node { int data; struct Node* next; }; 2️⃣ Insertion Insertion was implemented at:

The beginning.

The end.

Any given position.

This helped in understanding pointer updates and memory management.

3️⃣ Deletion Implemented deletion of:

The first node.

The last node.

A node at a specific position.

This helped me understand how to safely free memory to avoid memory leaks.

4️⃣ Traversal Implemented to print all node values sequentially, verifying correct linking between nodes.

Sample Output rust Copy Edit Linked List: 10 -> 20 -> 30 -> NULL After inserting at beginning: Linked List: 5 -> 10 -> 20 -> 30 -> NULL After deleting position 2: Linked List: 5 -> 10 -> 30 -> NULL Skills Learned ✅ Understanding pointers and memory management in C. ✅ Use of dynamic memory allocation (malloc, free). ✅ Hands-on with data structures and algorithm implementation. ✅ Debugging segmentation faults and pointer-related errors. ✅ Writing clean, modular C programs.

Challenges Faced Handling segmentation faults due to incorrect pointer assignments.

Properly freeing memory during deletion to avoid memory leaks.

Managing edge cases like empty list, single-node deletion, and invalid positions.

Conclusion This internship task helped me gain practical experience in implementing data structures using C, essential for placements and competitive coding. It deepened my concepts of pointers, dynamic memory, and linked data representation.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Footer
