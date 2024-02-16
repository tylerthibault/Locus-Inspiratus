---
{"tags":["CyberSecurity"],"template":"[[CyberSec Template]]","dg-publish":true,"permalink":"/600-coding/security/google-cyber-sec/cybersec-linux-commands/","dgPassFrontmatter":true}
---

## Common Commands
### cat

The cat command displays the content of a file. For example, entering cat updates.txt returns everything in the updates.txt file.

### head

The head command displays just the beginning of a file, by default 10 lines. The head command can be useful when you want to know the basic contents of a file but don’t need the full contents. Entering head updates.txt returns only the first 10 lines of the updates.txt file.

**Pro Tip**: If you want to change the number of lines returned by head, you can specify the number of lines by including -n. For example, if you only want to display the first five lines of the updates.txt file, enter head -n 5 updates.txt.

### tail

The tail command does the opposite of head. This command can be used to display just the end of a file, by default 10 lines. Entering tail updates.txt returns only the last 10 lines of the updates.txt file.

**Pro Tip**: You can use tail to read the most recent information in a log file.

### less

The less command returns the content of a file one page at a time. For example, entering less updates.txt changes the terminal window to display the contents of updates.txt one page at a time. This allows you to easily move forward and backward through the content. 

Once you’ve accessed your content with the less command, you can use several keyboard controls to move through the file:

- Space bar: Move forward one page
    
- b: Move back one page
    
- Down arrow: Move forward one line
    
- Up arrow: Move back one line
    
- q: Quit and return to the previous terminal window

### Using chmod

The chmod command requires two arguments. The first argument indicates how to change permissions, and the second argument indicates the file or directory that you want to change permissions for.  For example, the following command would add all permissions to login_sessions.txt:

chmod u+rwx,g+rwx,o+rwx login_sessions.txt

If you wanted to take all the permissions away, you could use

chmod u-rwx,g-rwx,o-rwx login_sessions.txt

Another way to assign these permissions is to use the equals sign (=) in this first argument. Using = with chmod sets, or assigns, the permissions exactly as specified. For example, the following command would set read permissions for login_sessions.txt for user, group, and other:

chmod u=r,g=r,o=r login_sessions.txt

This command overwrites existing permissions. For instance, if the user previously had write permissions, these write permissions are removed after you specify only read permissions with =.

The following table reviews how each character is used within the first argument of chmod:

|**Character**|**Description**|
|---|---|
|u|indicates changes will be made to user permissions|
|g|indicates changes will be made to group permissions|
|o|indicates changes will be made to other permissions|
|+|adds permissions to the user, group, or other|
|-|removes permissions from the user, group, or other|
|=|assigns permissions for the user, group, or other|

**Note:** When there are permission changes to more than one owner type, commas are needed to separate changes for each owner type. You should not add spaces after those commas.

## Users
### useradd

The useradd command adds a user to the system. To add a user with the username of fgarcia with sudo, enter sudo useradd fgarcia. There are additional options you can use with useradd:

- -g: Sets the user’s default group, also called their primary group
    
- -G: Adds the user to additional groups, also called supplemental or secondary groups
    

To use the -g option, the primary group must be specified after -g. For example, entering sudo useradd -g security fgarcia adds fgarcia as a new user and assigns their primary group to be security.

To use the -G option, the supplemental group must be passed into the command after -G. You can add more than one supplemental group at a time with the -G option. Entering sudo useradd -G finance,admin fgarcia adds fgarcia as a new user and adds them to the existing finance and admin groups.

### usermod

The usermod command modifies existing user accounts. The same -g and -G options from the useradd command can be used with usermod if a user already exists. 

To change the primary group of an existing user, you need the -g option. For example, entering sudo usermod -g executive fgarcia would change fgarcia’s primary group to the executive group.

To add a supplemental group for an existing user, you need the -G option. You also need a -a option, which appends the user to an existing group and is only used with the -G option. For example, entering sudo usermod -a -G marketing fgarcia would add the existing fgarcia user to the supplemental marketing group.

**Note:** When changing the supplemental group of an existing user, if you don't include the -a option, -G will replace any existing supplemental groups with the groups specified after usermod.  Using -a with -G ensures that the new groups are added but existing groups are not replaced.

There are other options you can use with usermod to specify how you want to modify the user, including:

- -d: Changes the user’s home directory.
    
- -l: Changes the user’s login name.
    
- -L: Locks the account so the user can’t log in.
    

The option always goes after the usermod command. For example, to change fgarcia’s home directory to /home/garcia_f, enter sudo usermod -d /home/garcia_f fgarcia. The option -d directly follows the command usermod before the other two needed arguments.

### userdel

The userdel command deletes a user from the system. For example, entering sudo userdel fgarcia deletes fgarcia as a user. Be careful before you delete a user using this command.

The userdel command doesn’t delete the files in the user’s home directory unless you use the -r option. Entering sudo userdel -r fgarcia would delete fgarcia as a user and delete all files in their home directory. Before deleting any user files, you should ensure you have backups in case you need them later.

**Note**: Instead of deleting the user, you could consider deactivating their account with usermod -L. This prevents the user from logging in while still giving you access to their account and associated permissions. For example, if a user left an organization, this option would allow you to identify which files they have ownership over, so you could move this ownership to other users.

### chown

The chown command changes ownership of a file or directory. You can use chown to change user or group ownership. To change the user owner of the access.txt file to fgarcia, enter sudo chown fgarcia access.txt. To change the group owner of access.txt to security, enter sudo chown :security access.txt. You must enter a colon (:) before security to designate it as a group name.

Similar to useradd, usermod, and userdel, there are additional options that can be used with chown.
## Filtering for information

You previously explored how filtering for information is an important skill for security analysts. **Filtering** is selecting data that match a certain condition. For example, if you had a virus in your system that only affected the .txt files, you could use filtering to find these files quickly. Filtering allows you to search based on specific criteria, such as file extension or a string of text.

### grep

The grep command searches a specified file and returns all lines in the file containing a specified string. The grep command commonly takes two arguments: a specific string to search for and a specific file to search through.

For example, entering grep OS updates.txt returns all lines containing OS in the updates.txt file. In this example, OS is the specific string to search for, and updates.txt is the specific file to search through.


## find

The find command searches for directories and files that meet specified criteria. There’s a wide range of criteria that can be specified with find. For example, you can search for files and directories that

- Contain a specific string in the name,
    
- Are a certain file size, or
    
- Were last modified within a certain time frame.
    

When using find, the first argument after find indicates where to start searching. For example, entering `find /home/analyst/projects` searches for everything starting at the projects directory.

After this first argument, you need to indicate your criteria for the search. If you don’t include a specific search criteria with your second argument, your search will likely return a lot of directories and files. 

Specifying criteria involves options. **Options** modify the behavior of a command and commonly begin with a hyphen (-). 

### -name and -iname

One key criteria analysts might use with find is to find file or directory names that contain a specific string. The specific string you’re searching for must be entered in quotes after the -name or -iname options. The difference between these two options is that -name is case-sensitive, and -iname is not. 

For example, you might want to find all files in the projects directory that contain the word “log” in the file name. To do this, you’d enter `find /home/analyst/projects -name "*log*"`. You could also enter `find /home/analyst/projects -iname "*log*"`.

In these examples, the output would be all files in the projects directory that contain log surrounded by zero or more characters. The "*log*" portion of the command is the search criteria that indicates to search for the string “log”. When -name is the option, files with names that include Log or LOG, for example, wouldn’t be returned because this option is case-sensitive. However, they would be returned when -iname is the option.

**Note**: An asterisk (\*) is used as a wildcard to represent zero or more unknown characters.

### -mtime

Security analysts might also use find to find files or directories last modified within a certain time frame. The -mtime option can be used for this search. For example, entering find /home/analyst/projects -mtime -3 returns all files and directories in the projects directory that have been modified within the past three days. 

The -mtime option search is based on days, so entering -mtime +1 indicates all files or directories last modified more than one day ago, and entering -mtime -1 indicates all files or directories last modified less than one day ago. 

**Note:** The option -mmin can be used instead of -mtime if you want to base the search on minutes rather than days.

## Piping

The pipe command is accessed using the pipe character (|). **Piping** sends the standard output of one command as standard input to another command for further processing. As a reminder, **standard output** is information returned by the OS through the shell, and **standard input** is information received by the OS via the command line. 

The pipe character (|) is located in various places on a keyboard. On many keyboards, it’s located on the same key as the backslash character (\). On some keyboards, the | can look different and have a small space through the middle of the line. If you can’t find the |, search online for its location on your particular keyboard.

When used with grep, the pipe can help you find directories and files containing a specific word in their names. For example, ls /home/analyst/reports | grep users returns the file and directory names in the reports directory that contain users. Before the pipe, ls indicates to list the names of the files and directories in reports. Then, it sends this output to the command after the pipe. In this case, grep users returns all of the file or directory names containing users from the input it received.

**Note:** Piping is a general form of redirection in Linux and can be used for multiple tasks other than filtering. You can think of piping as a general tool that you can use whenever you want the output of one command to become the input of another command.
## Standard output redirection

There’s an additional way you can write to files. Previously, you learned about standard input and standard output. **Standard input** is information received by the OS via the command line, and **standard output** is information returned by the OS through the shell.

You’ve also learned about piping. **Piping** sends the standard output of one command as standard input to another command for further processing. It uses the pipe character (|). 

In addition to the pipe (|), you can also use the right angle bracket (>) and double right angle bracket (>>) operators to redirect standard output.

When used with echo, the > and >> operators can be used to send the output of echo to a specified file rather than the screen. <mark class="hltr-red">The difference between the two is that > overwrites your existing file</mark>, and <mark class="hltr-orange">>> adds your content to the end of the existing file instead of overwriting it.</mark> The > operator should be used carefully, because it’s not easy to recover overwritten files.

When you’re inside the directory containing the permissions.txt file, entering echo "last updated date" >> permissions.txt adds the string “last updated date” to the file contents. Entering echo "time" > permissions.txt after this command overwrites the entire file contents of permissions.txt with the string “time”.

**Note:** Both the > and >> operators will create a new file if one doesn’t already exist with your specified name.

## Integrated Linux support

Linux also has several commands that you can use for support.

### **man**

The man command displays information on other commands and how they work. It’s short for “manual.” To search for information on a command, enter the command after man. For example, entering man chown returns detailed information about chown, including the various options you can use with it. The output of the man command is also called a “man page.”

### **apropos**

The apropos command searches the man page descriptions for a specified string. Man pages can be lengthy and difficult to search through if you’re looking for a specific keyword. To use apropos, enter the keyword after apropos. 

You can also include the -a option to search for multiple words. For example, entering apropos -a graph editor outputs man pages that contain both the words “graph" and "editor” in their descriptions.

### **whatis**

The whatis command displays a description of a command on a single line. For example, entering whatis nano outputs the description of nano. This command is useful when you don't need a detailed description, just a general idea of the command. This might be as a reminder. Or, it might be after you discover a new command through a colleague or online resource and want to know more.