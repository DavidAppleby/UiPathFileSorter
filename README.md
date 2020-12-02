# UiPath File Sorter

#### Warning! If you are a current Udacity student please abide by the Udacity Honor Code and do not plagiarize my work. You are ultimately responsible for your learning and conduct and I am not responsible if you are dropped from the program due to plagiarism. 

UiPath is the RPA tool for this project. The bot is programmed to perform the following tasks:
1) Download a zip file from GitHub to the local Downloads directory
2) Move the zip file to the project directory 
3) Extract the contents of the zip file
4) Sort the files into appropriate directory based on the file naming convention and the file type.

If files are of type pdf or xlsx and the file name is in format filename_DDMMYYYY, the file should be moved to a directory based on the year portion of the file name.
If the file is a different type or the filename is set by a different format, the file is moved to a directory named with the current date. 
