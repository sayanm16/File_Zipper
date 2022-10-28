# File_Zipper
A File Zipper made using Huffmann Algorithm.
This project supports two functions:
1) Encode: Compresses input file passed.
2) Decode: Decompresses Huffman coded file passed back to its original file.
3) struct Node represents a node of Huffman Tree which is generated during compression or decompression of files. It stores character data, its frequency, Huffman code, and two pointers that point towards the left or right node if they exist.


And a constructor which accepts input file and output file. The object of this class can be initiated as follows: huffman h(inputFileName, outputFileName);
