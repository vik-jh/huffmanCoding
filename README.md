# huffmanCoding
Huffman coding is none approach followed for Text Compression. Text compression means reducing the space requirement for saving particular text. 
Huffman Coding is a lossless data compression algorithm. They can be compressed without loosing their information
Steps: 
1. Begin with calculating the frequency of each character value in the given string
2. Sort the characters in ascending order concerning their frequency and store them in a priority queue, say Q
3. Each character should be considered as a different leaf node. 
4. Make an empty node, say z. The left child of z is marked as the minimum frequency and the right child, the second minimum frequency. The value of z is calculated by summing up the first two frequencies. 
5. Now, remote the two characters with the lowest frequencies from the priority queue (Q) and append their sum to the same. 
6. Simply insert the above node z to the tree
7. For every character in the string, repeat steps 3 to 5
8. Assign 0 to the left side and 1 to the right side except for the leaf nodes. 
