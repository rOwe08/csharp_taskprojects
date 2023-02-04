Program capable of constructing a Huffman tree for a specific file and
then using it for producing a compressed version of the file. The
program receives the name of the file in the form of a single
command-line argument, read all data from the input file and then
proceed with the Huffman tree building and compression. The compressed
file will be written to a binary file whose name is gained by adding the
.huff extension to the input file name.

If the program does not receive exactly one argument, the following
string is be printed out to standard output: 
**_Argument Error_**

In case of problems encountered when opening (e.g. the file does not
exist, insufficient access rights) or reading the file, the program
should output the following string to standard output: 
**_File Error_**

The input file can have any format (i.e. it can be a binary file).
