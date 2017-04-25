# Huffman-Encoding-and-Decoding
Huffman Encoding and Decoding in MATLAB

Steps to encode data using Huffman coding
Step 1. Compute the probability of each character in a set of data.
Step 2. Sort the set of data in ascending order.
Step 3. Create a new node where the left sub-node is the lowest frequency in the sorted list and the right sub-node is the second lowest in the sorted list.
Step 4. Remove these two elements from the sorted list as they are now part of one node and add the probabilities. The result is the probability for the new node.
Step 5. Perform insertion sort on the list.
Step 6. Repeat steps 3, 4 and 5 until you have only one node left.
