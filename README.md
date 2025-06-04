# Huffman Algorithm

This project implements the **Huffman Coding Algorithm**, a popular technique for **lossless data compression**. Huffman coding assigns shorter binary codes to more frequent characters, reducing the overall file size.

## 📌 Features

- Build a frequency table from input text
- Construct a Huffman Tree
- Generate binary codes for each character
- Encode and decode strings using the Huffman Algorithm

## 🧠 How It Works

1. Count the frequency of each character in the input.
2. Create a priority queue (min-heap) of all characters based on their frequency.
3. Repeatedly extract the two lowest-frequency nodes and combine them into a new internal node.
4. Assign binary codes to characters: left = `0`, right = `1`.
5. Encode the original string using the generated codes.

## 📂 Files

- `main.cpp`: Main driver of the program
- `Huffman.h`: Header file for Huffman tree and encoding logic
- `Huffman.cpp`: Implementation of the Huffman algorithm
