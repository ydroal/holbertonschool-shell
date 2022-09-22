#Shell, basics

##what each script is doing?

###Task0. Where am I?
---------------------
#!/bin/bash
pwd
---------------------
prints the absolute path name of the current working directory


###Task1. What’s in there?
---------------------
#!/bin/bash
ls
---------------------
Display the contents list of your current directory.


###Task2. There is no place like home
---------------------
#!/bin/bash
cd
---------------------
changes the working directory to the user’s home directory.


###Task3. The long format
---------------------
#!/bin/bash
ls -l
---------------------
Display current directory contents in a long format


###Task4. Hidden files
---------------------
#!/bin/bash
ls -la
---------------------
Display current directory contents, including hidden files (starting with .). Use the long format.


###Task5. I love numbers
---------------------
#!/bin/bash
ls -lan
---------------------
Display current directory contents, including hidden files (starting with .)with user and group IDs displayed numerically. Use the long format.


###Task6. Welcome
---------------------
#!/bin/bash
mkdir /tmp/my_first_directory
---------------------
Create a script that creates a directory named my_first_directory in the /tmp/ directory.


###Task7. Betty in my first directory
---------------------
#!/bin/bash
mv /tmp/betty /tmp/my_first_director
---------------------
Move the file betty from /tmp/ to /tmp/my_first_directory


###Task8. Bye bye Betty 
---------------------
#!/bin/bash
rm /tmp/my_first_directory/betty
---------------------
Delete the file betty



###Task9. Bye bye My first directory
---------------------
#!/bin/bash
rm -r  /tmp/my_first_directory
---------------------
Delete the file betty



###Task10. Back to the future
---------------------
#!/bin/bash
cd -
---------------------
Write a script that changes the working directory to the previous one.



###Task11. Lists
---------------------
#!/bin/bash
ls -la . .. /boot
---------------------
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.









