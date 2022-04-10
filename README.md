# Double-Linkedlist
-------------------------------->IIT BOMBAY<--------------------------------------------


 
  
   
    Doubly Linked List (DLL) is a complex data structure and an advanced version of a simple linked list in which the node has a pointer to the next node only. As we can traverse the elements in only one direction, reverse traversing is not possible. To solve this problem, a doubly-linked list came into the picture as each node contains the address of the previous and next node, so both the forward and backward traversing of the list is possible. So every node in a doubly-linked list contains 3 parts, i.e., the node which stores the actual item and the other parts contain the pointers containing the address of the previous and next node in the sequence. In this topic, we are going to learn about the Doubly linked list in C.

Syntax:

As every node in the sequence in a doubly-linked list contains 3 parts and stores the address of the next and previous nodes, it is implemented as follows in a C program:

struct node {
struct previous*;
int item;
struct next*
} node_name;
where,

previous: It is a pointer that stores the address of the previous node in the sequence.

next: It is a pointer that stores the address of the next node in the sequence.

item: It is the actual data that is stored in the doubly linked list.
node_name: It is a name given to a whole node on the C program.
