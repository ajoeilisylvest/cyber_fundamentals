## Linux Basics 2


### SSH:
- Allows us to remotely execute commands on another device
- Any data sent between the devices is encrypted when it is sent over a network such as the Internet
- Note: When you type a password into an login prompt there is no visible feedback -- you will not be able to see any text or symbols appear as you type the password

---

### About commands:

**Flags and switches:** 
- A majority of commands allow for arguments to be provided. These arguments are identified by a hyphen and a certain keyword known as flags or switches
- When using a command, unless otherwise specified, it will perform its default behaviour. For example, ls lists the contents of the working directory. However, hidden files are not shown. We can use flags and switches to extend the behaviour of commands.

**-a** : Short for all. When added to fx. ls will output ALL contents of current directory, including hidden files and folders.

**--help** : Will list the possible options that the command accepts, provide a brief description and example of how to use it.

**The manual pages** : A great source of information for both system commands and applications. To access this documentation, we can use the man command and then provide the command we want to read the documentation for. 

---

### More commands:

**touch <file_name>** :	Create file. (Use a text editor such as nano to add content to the file)

**mkdir <directory_name>** :	(Make Directory) Create a folder

**cp <name> <new_name>** : Copy a file or folder

**mv <file_name> <folder_name> OR <name> <new_name>** : Move a file or folder OR rename file or folder

**rm -R <name>** : Remove a file or folder

**file <file_name>** : Determine the type of a file

---

### Permissions




