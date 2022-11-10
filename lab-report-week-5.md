### **Lab Report 3 Week 5** by Emily Mills

## Fist Command: **Find - delete**
**Example 1**

Input:

![image 1](week_5_images/FIND%20DELETE%201.png)
Output:

![image 2](week_5_images/FIND%20DELETE%201%20OUTPUT.png)

This deletes everything found in find ./technical/911report/chapter* (all of the files in the 911 directory that start with "chapter"). We are left with preface.txt because all of the other files were deleted. 

**Example 2**

Input: 

![Image 3](week_5_images/FIND%20DELETE%202.png)

Output:

![Image 4](week_5_images/FIND%20DELETE%202%20OUTPUT.png)

This deletes the Media directory and all the contents inside of it. 

**Example 3**

Input: 

![Image 5](week_5_images/FIND%20DELETE%203.png)

Output:

![Image 6](week_5_images/FIND%20DELETE%203%20OUTPUT.png)

This deletes the file pmed.0020281.txt inside of plos. 

**Explanation of Find -delete**

Find -delete deletes all of the files/directories that it finds. The terminal does not ouput anything, but you can see that the file is deleted using the ls command in the parent directory. Additionally, if you try to call find on the file path after deleting it, you will get the output " No such file or directory".

## Second Command: **Find -type**

**Example 1**

Input and Output:

![image 7](week_5_images/FIND%20DELETE%204.png)

This command uses *find -type d*, which finds the directories that are inside of technical (including technical itself) (and inside all of the directories in technical, so on and so forth ).

**Example 2**

Input and Output:

![Image 8](week_5_images/FIND%20DELETE%205.png)

This command uses *find -type f* which finds the files that are inside of technical/911report. 


**Example 3**

Input and Output:

![Image 9](week_5_images/FIND%20DELETE%206.png)

This command uses *find -type d* which finds the directories that are inside of technical/biomed (includes technical/biomed itself). This shows that technical/biomed is a directory, but does not contain any directories inside of it.

**Explanation of Find -type**

The command *find -type* can be used to find files (-type f) or directories (-type d). 

## Third Command: **Find -size**

**Example 1**

Input and Output:

![Image 10](week_5_images/FIND%20DELETE%207.png)

This command uses *find -size 10b* to find all of the 10 byte files in technical and its' subdirectories.

**Example 2**

Input and Output:

![Image 11](week_5_images/FIND%20DELETE%208.png)

This command uses *find -size 1M* to find all of the 1 megabyte files in technical/911report.

**Example 3**

Input and Output: 

![Image 12](week_5_images/FIND%20DELETE%209.png)

This command uses *find -size 2k* to find all of the 2 kilobyte files in technical/government and its' subdirectories. 

**Explanation of Find -size**

The command *find -size* can be used with different inputs (b for bytes, k for kilobytes, and M for megabytes) in order to find files of a certain size. 









