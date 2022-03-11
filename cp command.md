cp command

cp stands for copy. This command is used to copy files or group of files or directory. 
It creates an exact image of a file on a disk with different file name. cp command require at least two filenames in its arguments.

Syntax:
cp [OPTION] Source Destination
cp [OPTION] Source Directory

Options
1. -i(interactive): i stands for Interactive copying. With this option system first warns the user before overwriting the destination file. 
    cp prompts for a response, if you press y then it overwrites the file and with any other option leave it uncopied.
    
2.-f(force):If the system is unable to open destination file for writing operation because the user doesn’t have writing permission for this file then by using -f option with cp command, 
    destination file is deleted first and then copying of content is done from source to destination file.
    
3.-r:Copying directory structure. With this option cp command shows its recursive behavior by copying the entire directory structure recursively.


Output

<img width="515" alt="cp command" src="https://user-images.githubusercontent.com/92944722/157804709-2b5950f3-10a6-4693-bfd9-f50802d54078.png">
