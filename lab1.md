![image](https://github.com/nataliehti/cse15l-lab-reports/assets/146873462/a7034255-9e5a-4f1a-be27-612d333fa2b4)# CSE 15L - Lab Report 1
Natalie Ti (A17510793)
Section: Tuesday, 10-11:50am B270


## Using the command `cd`

1. Without arguments, `cd` changes the directory back to the root directory. In this example, the working directory was lecture1, but cd changed it back to the home directory. 
   ![cd1](cse15l-lab1-image1.1.png)
   
2. With a directory argument, `cd` changes the directory, meaning future commands would be given within it. In this example, the working directory was the home directory user@sahara, but `cd` changed it to lecture1. 
   ![cd2](cse15l-lab1-image1.2.png)
   
5. With a file argument, an error is returned because the file is not a directory. `cd` is for directories and will not work on files. The working directory was lecture1, but it was trying to change to a java file instead of another directory.   
  ![cd3](cse15l-lab1-image1.3.png)


 
## Using the command `ls`

1. Without arguments, `ls` outputs all the file names in the workspace -- `ls` stands for "list arguments." The current working directory was the home directory user@sahara and so listed all the files in it. 
   ![ls1](cse15l-lab1-image2.1.png)  
     
2. With a directory, `ls` outputs all the file names in the directory. The working directory would be the specified argument lecture1, and so lists the files in the argument. 
   ![ls2](cse15l-lab1-image2.2.png)  
  
3. With a file, `ls` re-outputs the file path. Because Hello.java is just a file, `ls` relists the argument. `ls` does not change the working directory, so it remains the root.  
   ![ls3](cse15l-lab1-image2.3.png)


  
## Using the command `cat`

1. Without arguments, `cat` changes the input method. Whatever text the user puts into terminal, is returned back. `cat` does not change the working directory, so it remains the root.  
   ![cat1](cse15l-lab1-image3.1.png)  
  
2. With a directory, `cat` returns an error for an invalid input. `cat` stands for "concatenate," and cannot return the contents of a folder containing files. `cat` does not change the working directory, so it remains the root.  
   ![cat2](cse15l-lab1-image3.2.png)  
  
3. With a file, `cat` first imports libraries needed to convert the code in the file to a String, then outputs its contents as text. `cat` does not change the working directory, so it remains the root.    
   ![cat3](cse15l-lab1-image3.3.png)
