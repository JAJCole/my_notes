# My DS Notes
# This is a repository for my class notes at Codeup

after creating repo on github, copying ssh, open terminal
- git clone *ssh* then enter pw
- git status
- git add *filename*
- commit the work with git commit -m *FILE*
- push work with git push
- git log will display the change log
- to reset pushes, git reset --hard *copy/paste the commit log number


- *reminder* to create a file it is touch *filename.filetype*



# Terminal notes below
Within terminal ls lists the files in the directory you're in
Cd returns to start, ../ returns one directory up
If you know a specific location of the file you can input file name within " "
Pwd is print working directory

control+c stops terminal action
Control+z exits programs such as python within terminal

Make directory : mkdir *NAME*
Touch : make files within directory. Must specify type of file, like .txt or .py

To make hidden files or directories, add a "." in front (no quotes)

To find hidden files or directories, within the queried file type ls -a to display hidden too

To use a specific or default application for file types, use open

To force a specific application use open -a (where -a is not a directory flag but an application instruction) followed by program name ex: open -a TextEdit python_test.py

To move a file use mv *filename* ../ to move it up
Mv can also be used to rename. Which is: mv current_filename new_filename
(Link for mv here:  https://ds.codeup.com/fundamentals/cli/moving-files/)

To remove use rm for files, rmdir for directory (has to be empty) unless you use rm -r. Note that when using this, it permanently deletes forever. Not to the trash so *BEWARE*

To copy files within a directory, enter the directory and type cp to copy followed by the file you want to copy and the name of the resultant copy file: cp test1.txt test2.txt

To enter superuser mode, type sudo -s *BEWARE. You don't need this commonly but now you know*
To return to regular terminal type su - *account name* which in my case is jarredcole

Further info on terminal commands at:  https://ds.codeup.com/fundamentals/cli/more-topics/

Further resources: https://www.unix.com/man-page/FreeBSD/1/ls/


