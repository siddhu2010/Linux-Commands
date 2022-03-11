mv command

mv is used to move one or more files or directories from one place to another in a file system like UNIX.

Syntax: 

mv [Option] source destination

Option:

 -i (Interactive): Like in cp, the -i option makes the command ask the user for confirmation before moving a file that would overwrite an existing file,
 you have to press y for confirm moving, any other key leaves the file as it is.

-f (Force): mv prompts for confirmation overwriting the destination file if a file is write-protected. 
The -f option overrides this minor protection and overwrites the destination file forcefully and deletes the source file. 

-u (Update): move when source is newer than destination

Output

<img width="590" alt="mv commands" src="https://user-images.githubusercontent.com/92944722/157807143-1ae58926-af7e-4d20-bdbd-013b875116ce.png">
