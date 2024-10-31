##Complexity Analysis Report
1. Static Array
   Time Complexity
   Insertion:

Best Case: Θ(1)
Θ(1) when inserting at the end.
Average Case: Θ(𝑛)
Θ(n) when inserting at a random index (requires shifting elements).
Worst Case: 𝑂(𝑛)
O(n) when inserting at the beginning.

Deletion:

Best Case: Θ(1)
Θ(1) when deleting the last element.
Average Case: Θ(𝑛)
Θ(n) when deleting from a random index (requires shifting elements).
Worst Case: 𝑂(𝑛)
O(n) when deleting from the beginning.

Traversal:

Best Case: Θ(1)
Θ(1) when accessing a single element.
Average Case: Θ(𝑛)Θ(n).
Worst Case: 𝑂(𝑛)
O(n).
Space Complexity
Space Complexity: O(𝑛)
O(n), where 
n is the size of the array

2. Dynamic Array

   Time Complexity

   Insertion:

Best Case: Θ(1)
Θ(1) when there is space available.
Average Case: Θ(1)
Θ(1) when amortized over many insertions (due to occasional resizing).
Worst Case: 𝑂(𝑛)
O(n) when resizing the array.
Deletion:

Best Case: Θ(1)
Θ(1) when deleting the last element.
Average Case: Θ(𝑛)
Θ(n) when deleting from a random index.
Worst Case: 𝑂(𝑛)
O(n) when deleting from the beginning.
Traversal:

Best Case: Θ(1)
Θ(1) when accessing a single element.
Average Case: Θ(𝑛)
Θ(n).
Worst Case: 𝑂(𝑛)
O(n).
Space Complexity
Space Complexity: 𝑂(𝑛)
O(n), where 
n is the number of elements in the dynamic array.

3. String Operations
   
3.1 Run Length Encoding (RLE)
Encoding:

Best Case: Θ(𝑛)
Θ(n) for strings with all unique characters.
Average Case: O(n)
Worst Case: 𝑂(𝑛)
O(n) for strings with a high number of repetitions.
Decoding:

Best Case: Θ(𝑛)
Θ(n) when there are few encoded characters.
Average Case: Θ(𝑛)
Worst Case: 𝑂(𝑛)
O(n) when reconstructing the original string.

Space Complexity

Space Complexity: 
𝑂(𝑛)
O(n), where 
n is the length of the encoded string.
3.2 Knuth-Morris-Pratt (KMP) Algorithm

Time Complexity

Best Case: Θ(𝑛)
Θ(n) when the pattern matches immediately.
Average Case: Θ(𝑛)
Θ(n) for typical string matching.
Worst Case: 𝑂(𝑛+𝑚)
O(n+m), where 
n is the length of the text and m is the length of the pattern.

Space Complexity

Space Complexity: 
𝑂(𝑚)
O(m) for the LPS (Longest Prefix Suffix) array, where 
m is the length of the pattern.

This report summarizes the time and space complexity of the implemented algorithms using Big O, Omega, and Theta notations, highlighting best, average, and worst-case scenarios for each operation. Let me know if you need further elaboration or any modifications!
