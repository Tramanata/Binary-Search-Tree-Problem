# ECE 309 - Program 2: Binary Search Tree

## Assignment Overview

### Learning Objectives
- Binary search tree (BST) implementation.
- Understanding tree traversal and using it to complete the task.
- Solving problems in an object-oriented manner.

### Associated Files
- Assignment description (this document)
- Test input files (e.g., `request.txt`)
- Tree file (`tree.txt`)

### Description
In this program, you need to create a class for a binary search tree and use it to store data from `tree.txt`, which includes 9 distinct digit numbers in a given order (4, 2, 1, 3, 7, 6, 5, 9, 8). 

1. **Binary Search Tree Creation**: 
   - Read `tree.txt` and use the first item (4) as the root node.
   - Insert the remaining items to create a BST with the same structure as shown in Figure 1 of the assignment.

2. **Horizontal Display**:
   - Implement a method in your BST class called `horizon_display` to print the BST horizontally.
   - The output should have 9 lines with each line containing one number, spaced 5 spaces between tree levels.

3. **Processing Requests**:
   - Read and process `request.txt` to search for requests in the BST.
   - Count the total number of nodes visited after searching all requests.

4. **Frequency-Based BST**:
   - Create another BST based on the frequency of requests from `request.txt`.
   - Sort the 9 digit numbers in descending order of their frequency and create the BST.
   - Compare the total number of nodes visited for each request in the frequency-based BST.

### Implementation Steps
1. Parse the input parameters to determine the tree file and request file.
2. Create a BST based on the tree file.
3. Implement `horizon_display` to show its structure.
4. Derive the frequency of each number in the request file, sort them, and create another BST.
5. Process each request in `request.txt` and count the number of nodes visited.
6. Print the total number of nodes visited for searching all items in each BST structure.

### Report Format
- Print the frequency of each item in the request file.
- Output of `horizon_display` for both BSTs.
- Comparison of the total number of steps for each request file.

### Submission Format
- `main.cpp`
- `report.pdf`

### Grading Criteria
- 10 points: Files submitted with proper name.
- 10 points: Program is complete, takes 2 inputs, and returns the correct output.
- 10 points: Proper coding style and comments.
- 60 points: Program performs all functions correctly:
  - (15 pts) Create a BST class and implement the insert method based on `tree.txt`.
  - (15 pts) Correctly implement `horizon_display` and print the BST structure.
  - (20 pts) Correct frequency for each item in the request file and create another BST based on the frequency.
  - (10 pts) Correct results for request files.
- 10 points: Report.
