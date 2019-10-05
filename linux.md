# Linux and the basic commands
## 1. cd - change directory
To change the current working directory, we use the "cd" command (where "cd" stands for "change directory")
$ cd name-of-subfolder/sub-subfolder/

![Adding Image for cd](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/cd.JPG)

## 2. mkdir - make directory
To create a new folder, we use the mkdir command (where "mkdir" stands for "make directory")
Finally, to create a new folder, you call the "make directory" command:
$ mkdir new-folder

![Adding Image for mkdir](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/mkdir.JPG)

## 3. cp - Copy
The cp command is a command-line utility for copying files and directories. It supports moving one or more files or folders with options for taking backups and preserving attributes.
If, instead of moving the file, you want to copy it, simply use "cp" instead of "mv". 

## 4. pwd - Print Working Directory
To find out in which directory we are presently working, we use pwd command (where "pwd" stands for "print working directory").  It will return the path to a local folder on our computer's disk.
First command to find out where we currently are:
$ pwd

![Adding Image for pwd](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/pwd.JPG)

## 5. mv - move
To move a file or directory from one place to another, we use mv command (where "mv" stands for "move"). It is also used to rename a file.  It supports moving single files, multiple files and directories.

Moving a file is just as simple:
$ mv path/to/file.ext different/path/file.ext
The "mv" command can also be used to rename a file:
$ mv old-filename.ext new-filename.ext

![Adding Image for mv](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/mv.JPG)

## 6. rm - remove 
To remove the file from the directory, we use rm command (where "rm" stands for "remove").It removes each file specified on the command line. When rm is executed with the -r or -R options, it recursively deletes any matching directories

Let's start by removing a file:
$ rm path/to/file.ext
When trying to delete a folder, however, please note that you'll have to add the "-r" flag (which stand for "recursive"):
$ rm -r path/to/folder

![Adding Image for rm](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/rm.JPG)

## 7. History 
The History command is used to view the previously executed command

![Adding Image for History](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/History.JPG)

## 8. ~ - Tilde
To know users account home folder, we use ~. Instead of typing something like "cd /Users/your-username/projects/", we use this notation  "cd ~/project"
 
## 9. File paths in linux 
A path is a unique location to a file or a folder in a file system of an OS. A path to a file is a combination of / and alpha- numeric characters.

## 10. Using the tab key to complete file paths
Whenever we enter file names we use the TAB key. It autocompletes the file names including paths to a file or directory.
For example, when you want to switch to a different directory, you can either type every component of the path yourself:
$ cd ~/projects/acmedesign/documentation/

Or you make use of the TAB key (try this yourself!):
$ cd ~/pr[TAB]ojects/ac[TAB]medesign/doc[TAB]umentation/

## 11. Using up and down arrow for history
We can step through the last commands we called (starting with the most recently used) by using the Arrow UP key
and Arrow DOWN helps in moving forward in history towards the most recent cell. 

## 12. Home Directory 
A home directory, also called a login directory, is the directory on Unix-like operating systems that serves as the repository for a user's personal files, directories and programs. It is also the directory that a user is first in after logging into the system.

![Adding Image for Home Directory](https://github.com/Snehaphilip989/miniproject1/blob/master/Images/home%20directory.JPG)
