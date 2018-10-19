###Part I  
1. make a directory called first  
mkdir first
2. change directory to the first folder   
cd first  
3. create a file called person.txt  
touch person.txt
4. change the name of person.txt to another.txt  
mv person.txt another.txt  
5. make a copy of the another.txt file and call it copy.txt  
6. remove the copy.txt file  
rm copy.txt
7. make a copy of the first folder and call it second  
cp -r first second
8. delete the second folder    
rm -rf second

###Part II
1. What does the man command do? Type in man rm. How do you scroll and get out?   
The man command lists the manual for whatever command you give it. You can scroll down by either using the down arrow or the key D, you can scroll up by either using the up arrow or the key U, and you get out by pressing the key Q  
2. Look at the man page for ls. What does the -l flag do? What does the -a flag do?    
the -l flag lists in long format. the -a flag includes directory entries whose names begin with a dot (.)
3. Type the following command to download and save the contents of google.com: curl https://www.google.com > google.html
4. Use less to look at the contents of google.html.    
less google.html
5. Look at the man page for less. Read the section on /pattern. Search for the text hplogo in the google.html file.    
less -p hplogo google.html
6. How do you jump between words in the terminal?    
option left/right
7. How do you get to the end of a line in terminal?    
control + e
8. How do you move your cursor to the beginning in terminal?    
control + a
9. How do you delete a word (without pressing backspace multiple times) in terminal?    
option + delete
10. What is the difference between a terminal and shell?    
A terminal is an application that gives us command line interface to interact with the computer. It is the wrapper program that runs a shell. Shell is the program that actually processes commands and returns output. It also manages the foregroudn and background processes. 
11. What is an absolute path?    
And absolute path is when we specify a path starting from the root directory /
12. What is an relative path?    
A relative path is relative to where we are currently, so it starts at the current location instead of the root route. 
13. What is a flag? Give three examples of flags you have used.    
A flag is used to modify behavior of the commands. -a lists all files. -l gives more information about each file. -h specifies to use unit suffixes
14. What do the r and f flags do with the rm command?    
When passes to the rm command, the r flag removes folders, and the f flag will force removal 












