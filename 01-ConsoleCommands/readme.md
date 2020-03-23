# Bash / Terminal Commands

## Instructions

- From the Terminal/Console and using only the command line, create the following:
  - A new folder with the name of first_day_stuff
  - A new HTML file with the name of first-day.html
  - Open the current folder containing the new HTML file.

## BONUS

- Create multiple directories/folders with the names `one_folder` and `second_folder` in one command.
- Create multiple files with the names `one.html` and `two.html` in one command in the first_day_stuff directory.
================================================================================================================================
# Open Terminal Navigate to your Desktop  
Create a new directory, call it 'test'
Make files called index.html, styles.css, commands.txt inside the test directory  
Make a copy of index.html and call it index_2.html  
In the 'test' directory, remove the 'styles.css' file  
Navigate back to your desktop and make another directory, call it 'destination'  
Move the index_2.html file from 'test' to the 'destination' directory  
Now, check and see what files are in the 'test' and 'destination' directories Delete the 'destination' directory  
Write the commands you used to do the above and save them in commands.txt.
Then upload it below!  
Spend 10 minutes researching some other terminal commands and keep them in mind for the future!
=============================================================================================================================
# Solutions:
cd desktop/
mkdir test
cd test
touch index.html styles.css commands.txt
cp index.html index_2.html
rm styles.css
cd ..
mkdir destination
mv test/index_2.html destination/
cd destination
ls
cd ..
cd test
ls
cd ..
rm -rf destination
================================================================================================================================