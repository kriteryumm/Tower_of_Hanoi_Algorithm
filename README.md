# Tower of Hanoi 
A stack of disks needs to be transferred from one rod to another in the well-known math challenge known as the Tower of Hanoi while following these rules:

There are three rods and various disks with different diameters.
The disks are first placed on a single rod in a neat size sequence, with the smallest disk at the top creating a conical shape.
The objective of the puzzle is to move the entire stack to a new rod while following these fundamental rules:


![Screenshot 2024-01-25 15 39 55](https://github.com/kriteryumm/Tower_of_Hanoi_Turtle/assets/61352431/b11755ee-9f81-4ec8-9e49-ffd71aca8284)


1 - Only one disk at a time may be moved.
2 - With every move, the tallest disk from a stack is taken out and either placed on top of another stack or on an empty rod.
3 - No disk can be placed on top of another disk that is smaller than itself. 

For solving this game we used two algorithm.
Recursive Algorithm
1. To solve recursively the puzzle of shifting top 3 disk from Rod A to Rod B
2. To move the largest disk to Rod C
3. To solve recursively the puzzle of shifting disk on Rod B to Rod C

Recursion Algorithm
hanoi(n, start, end) provides a set of instructions to move n disks from the starting rod to the destination rod. 
There are some assumptions to consider:

The starting rod is between 1 and 3 (1≤ Start ≤3).
The destination rod is between 1 and 3 (1≤ End ≤3).
The starting rod is not the same as the destination rod (Start ≠ End).


In this code you will see how these algoritm works and the output of this algorithms with turtle library.

## Results
For result you can check the execution time for both algoritm.

![image](https://github.com/kriteryumm/Tower_of_Hanoi_Turtle/assets/61352431/b5a7e1f8-e895-452d-95f8-4c8e50ccf822)

