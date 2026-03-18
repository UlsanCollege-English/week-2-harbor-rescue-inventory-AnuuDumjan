[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/HYC1dWeQ)
# Week 2 README Template

## Summary
The Harbor Rescue Inventory assignment uses Python lists to manage rescue supplies.
It includes functions that check the first and last items, return parts of a list, find item positions, and count supplies.
The goal is to practice list operations such as slicing, searching, and counting.
These functions help rescuers quickly understand what items are available.

## Approach
mission_snapshot:
Returns the first and last items from the list. If the list is empty, it returns (None, None).

cargo_window:
Returns a slice of the list starting from a specific index and including up to the given size.

first_supply_index:
Uses a loop to find the first position of the target item. Returns -1 if the item is not found.

supply_report:
Counts how many times the target item appears in the list and also returns the first index.

priority_load (stretch):
Creates a new list with the urgent item added at the beginning without modifying the original list.

## Complexity reasoning

| Function                  | Time complexity | Why                                      |
| ------------------------- | --------------- | ---------------------------------------- |
| `mission_snapshot`        | O(1)            | Only accesses first and last element     |
| `cargo_window`            | O(k)            | Returns a slice of size `k`              |
| `first_supply_index`      | O(n)            | May check every element in the list      |
| `supply_report`           | O(n)            | Iterates through the list to count items |
| `priority_load` (stretch) | O(n)            | Creates a new list with the urgent item  |


## Edge-case checklist
 - [x] empty list
- [x] one-item list
- [x] target missing
- [x] repeated values
- [x] slice goes past end
- [x] size is zero
- [x] size is negative
- [x] original list unchanged in priority_load

## Assistance / Sources

## Assistance / Sources

Person / tool / website: ChatGPT  
Help received: Helped explain the assignment instructions and structure the README.

Person / tool / website: Google  
Help received: Used for general Python list documentation and syntax reference.