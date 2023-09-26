# Palindrome Linked List Checker

## Description

This Python program checks if a given linked list is a palindrome. A palindrome linked list is one that reads the same forward and backward.

## Usage

1. Ensure you have Python installed on your system.
2. Copy and paste the provided Python program maian.py into your project.
3. Create a linked list and call the `is_palindrome` function with the head of the linked list.

```python
# Example Usage
# Create a linked list: 1 -> 2 -> 3 -> 2 -> 1
head = ListNode(1)
head.next = ListNode(2)
head.next.next = ListNode(3)
head.next.next.next = ListNode(2)
head.next.next.next.next = ListNode(1)

result = is_palindrome(head)
print(result)  # Output: True
