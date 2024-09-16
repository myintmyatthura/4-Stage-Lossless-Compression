# Multi-Layered Compression with **Run-Length Encoding and Huffman Coding** written in **Haskell**

---

## A tool to compress and decompress text files using multiple lossless compression algorithms, with command-line support for layered compression.

---

A versatile and memory-efficient compression tool built in Haskell, featuring support for multiple lossless algorithms like Run-Length Encoding (RLE) and Huffman Coding. Ideal for compressing and decompressing text files in layered sequences for more efficient data storage and transfer. The tool supports flexible command-line arguments to easily control the compression and decompression process.

**Features:**

- Compress and decompress text files using
  multiple algorithms (RLE, Huffman Coding)
- Apply multiple layers of compression for better
  results
- Command-line interface for flexible control
  over compression sequences
- Expandable to support additional compression
  algorithms in the future
- Fully lossless, ensuring exact data recovery
  upon decompression
- Efficient and easy-to-use for text file
  compression tasks

---

**Pre-requisites for execution:**

- Have Haskell and GHC installed
- No external compression libraries needed
- Dependencies: None beyond standard Haskell libraries

---

**How to use:**

Running this command will automatically compress or decompress your text file using the specified algorithms.

```
./manifold compress "rle huffman" input_file output_file
./manifold decompress "huffman rle" input_file output_file
```
