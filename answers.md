# CMPS 2200 Recitation 6
## Answers

**Name:** Collette Riviere 


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt       |     1340    |      826       |     0.616418
alice29.txt  |   1039367   |     676374     |     0.650756
asyoulik.txt |    876253   |     606448     |     0.692092
grammar.lsp  |    26047    |     17356      |     0.666334
fields.c     |    78050    |     56206      |     0.720128

The ratio of Huffman to Fixed-length is always around 0.66. 

- **e.**

If all the characters had the same frequency, the tree would be balanced so the cost would be just the depth of the tree which is log n, where n is the size of the alphabet.