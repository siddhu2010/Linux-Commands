cmp command

cmp command in Linux/UNIX is used to compare the two files byte by byte and helps you to find out whether the two files are identical or not.

Syntax:
cmp [OPTION]... FILE1 

1. -b(print-bytes) : 
    If you want cmp displays the differing bytes in the output when used with -b option.
2. -l option : 
    This option makes the cmp command print byte position and byte value for all differing bytes.
3. -s option : 
    This allows you to suppress the output normally produced by cmp command i.e it compares two files without writing any messages. 
    This gives an exit value of 0 if the files are identical, a value of 1 if different, or a value of 2 if an error message occurs.


Output

<img width="422" alt="cmp commands" src="https://user-images.githubusercontent.com/92944722/157804098-d560b183-893f-4d0f-9068-e54a3c94297b.png">
