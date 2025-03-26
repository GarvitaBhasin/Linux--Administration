🚀 LAB 3 - 4 🚀
1. View the gedit man page.

2. Use the man -k ext4 command to find the command to tune ext4 file-system parameters.

3. Understand and demonstrate the use of brace expansion.
Solution :
Lab 3:
Open the terminal and type: man gedit

<img width="120" alt="image" src="https://github.com/user-attachments/assets/73285c6e-3cdc-4d0c-8755-b0a77704f306" />


If the manual page is not available, try installing gedit first: sudo apt update && sudo apt install gedit

image

Lab 4:
To search for commands related to ext4, type:
man -k ext4

image

To find the command to tune ext4 file systems, look for tune2fs in the output and check its manual page: man tune2fs

image

Understanding Brace Expansion:
echo file{1,2,3}.txt
Output:

file1.txt file2.txt file3.txt
image

Using a sequence expression: echo file{1..5}.txt

image
