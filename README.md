#  SequenceAssembly
  This task is related to Genomic Bioinformatics course. In this task you should assemble two types of reads using the De Bruijn graph representation and the Eulerian path to obtain the original sequence from that representation.

First type of reads : Short reads with the same size.

Second type of reads : Pairreads with a known distance between them.

Input :
Your program should be able to read a file (for the single or paired
reads).

The first line would be:
- the length of the sequences (for single reads).
- the length of the sequences in each side and the length of the gap (for the paired reads).

Each read will take one.
The pair reads will be separated by “|” .. Example : AGCC|TTAA

Output : The program then outputs the assembled sequence to the screen. (or write it in a file).
