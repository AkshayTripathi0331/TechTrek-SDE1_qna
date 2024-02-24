# Linked Lists

## Introduction

Linked lists are linear data structures consisting of nodes where each node points to the next node in the sequence. Unlike arrays, linked lists do not have a fixed size and allow for efficient insertion and deletion of elements.

## Types of Linked Lists

- **Singly Linked List**: Each node points to the next node in the sequence.
- **Doubly Linked List**: Each node has two pointers, one pointing to the next node and another pointing to the previous node.
- **Circular Linked List**: Last node of the list points back to the first node.

## Operations

Common operations performed on linked lists include:

- **Insertion**: Adding a new node to the list.
- **Deletion**: Removing a node from the list.
- **Traversal**: Iterating through the list to access or modify nodes.
- **Search**: Searching for a specific value in the list.

## Common Interview Questions

### 1. Reverse a Linked List

**Description:**
Reverse a singly linked list.

**Example:**
Input: `1 -> 2 -> 3 -> 4 -> 5`
Output: `5 -> 4 -> 3 -> 2 -> 1`

**Solution:**
- Iterative Approach
- Recursive Approach

### 2. Detect a Cycle in a Linked List

**Description:**
Detect if a linked list has a cycle.

**Example:**
Input: `1 -> 2 -> 3 -> 4 -> 5 -> 2` (5 points back to 2)
Output: `True`

**Solution:**
- Floyd's Tortoise and Hare Algorithm

### 3. Merge Two Sorted Linked Lists

**Description:**
Merge two sorted linked lists into a single sorted list.

**Example:**
Input: `1 -> 3 -> 5` and `2 -> 4 -> 6`
Output: `1 -> 2 -> 3 -> 4 -> 5 -> 6`

**Solution:**
- Iterative Approach
- Recursive Approach

## Additional Resources

- [GeeksforGeeks - Linked List](https://www.geeksforgeeks.org/data-structures/linked-list/)
- [LeetCode - Linked List Problems](https://leetcode.com/tag/linked-list/)
- [Hackerrank - Linked List](https://www.hackerrank.com/domains/data-structures/linked-lists)

## Conclusion

Linked lists are versatile data structures with various applications in programming and are frequently encountered in technical interviews. Mastering linked list manipulation techniques and understanding common linked list problems can greatly enhance your problem-solving skills and prepare you for SDE1 interviews.

---

Feel free to expand upon each section with more detailed explanations, additional examples, and alternative solutions. Customizing the content according to your preferences and the needs of your audience will make the `Linked_List.md` file a valuable resource for SDE1 interview preparation.