# Let's learn about the Linux OS

# Why learn Linux OS?

Linux is a very powerful and versatile operating system, and knowing how to use it can open up a lot of opportunities for you in terms of both personal and professional development.

For example, many high-performance computing systems, such as supercomputers and cloud computing platforms, are based on Linux, so having Linux skills can be a valuable asset in fields that involve these types of systems. Additionally, Linux is an open-source operating system, which means that anyone can access and modify its source code.

This means that there is a large and active community of developers who contribute to Linux and make it better, and by learning Linux, you can become a part of this community and even contribute your own ideas and improvements.

Learning Linux is important in the field of DevOps for several reasons. First, many of the tools and technologies that are commonly used in DevOps, such as Docker, Kubernetes, and Ansible, are designed to run on Linux systems. In order to effectively use these tools, you need to have a good understanding of how Linux works and how to operate it.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671030176015/eBDAcZhXI.png align="center")

# Introduction to Shell

What is a shell? This command-line interface will enable you to work on your Linux system effectively. A graphical interface may seem more user-friendly, but it can be pretty limited in the level of functionality. As a Linux system admin, you would always need to know how to work with the shell.

The Linux shell is a powerful tool with which you can navigate between different locations within the system. So, When you log into the shell the very first directory you are taken to is your home directory. Every user has a home directory created under the "/home" directory. The home directory allows user to store their personal data in form files and folders.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671029949448/Hs_Z81mmh.png align="center")

## Different types of Shells

Now let's talk about the different types of shells.

*   Bourne shell (sh)
    
*   C shell (csh)
    
*   Korn shell (ksh)
    
*   The z shell (zsh)
    
*   Bourne again shell (bash)
    

These Shells may be in different ways in their core capabilities, but they have one common responsibility to communicate between the user and system.

To check which shell is being used :

```bash
[~]$ echo $SHELL
```

To change the default Shell then use this command:

```bash
[~]$ chsh -s /bin/zsh
```

### Some Features of bash shell

*   Directory manipulation, with the **pushd**, **popd**, and **dirs** commands.
    
*   Job control, including the **fg** and **bg** commands and the ability to stop jobs with CTRL-Z.
    
*   Brace expansion, for generating arbitrary strings.
    
*   Tilde expansion is a shorthand way to refer to directories.
    
*   Aliases, which allow you to define shorthand names for commands or command lines.
    
*   Command history, which lets you recall previously entered commands.
    

## Command-line help

In Simple terms, the 'man' command in Linux is **used to display the user manual of any command that we can run on the terminal**.

# Linux commands

## Basic Commands of Linux OS

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671030041822/C3k6NIEzf.jpg align="center")

### List operation

*   `ls` - Shows list.
    
    *   `-a` - Hidden file.
        
    *   `-l` - Permission.
        
    *   `-R` - Show sub dir.
        

### Changing dir operation

*   `cd <folder-name>` - Change Dir.
    
*   `cd ..` - Go one Directory back.
    
*   `cd` - Go home.
    
*   `cd ../<foldername>` - Open a previous dir folder.
    
*   `cd <path>` - Open a dir with the path.
    

### File/Folder Ope.

*   `mkdir <new-dir-name>` - Create a new folder.
    
*   `mkdir -p test/test1/test2` - Create a dir between two directories.
    
*   `touch <new-file-name>` - create a blank file.
    
*   `pwd` - Present working directory.
    
*   `cat <filename>` - Display file content.
    
*   `cat > <new-file-name>` - Create a file.
    
*   `dd if=/dev/zero of=bos_dosya bs=4G count=1`\- create an empty file with zeros
    
*   `cat >> <filename>` - Append the file.
    
*   `cat <filename> <filename2>` - Display 2 files at a time.
    
*   `cat <filename> <filename2> > <newfile-name>` - Merge both file content in a single one.
    
*   `cat <file-name> | tr > <new-file-name>` - Translate the file.
    
*   `cut -c 1-2 <filename>` - cut the file column wise
    
*   `echo "Hello" >> <file-name>`
    
*   `man <commad name>` - Know about the command usages and options.
    
*   `man <commad name>` - know about the command.
    

### File/Folder operation

*   `cp <file-name> <new-fie-name>` - Make a copy of a file in the current location.
    
*   `mv <file-name> <dir-path>` - Move a file from one dir to another.
    
*   `mv <file-name> <new-fie-name>` - Rename a file.
    
*   `mv -R <dir-name> <dir-path>` - Move Dir
    
*   `rm <file-name>` - Remove a file
    
*   `rm -R <file-name>` - Delete a folder with the dir included.
    
*   `head <file-name>` - Will display the first 10 lines of a file.
    
*   `tail <file-name>` - Will display the last 10 lines of a file. -`-n 2` - will display last 2 lines.
    
*   `diff <file-1> <file-2>` - Show diff between the two files.
    
*   `locate <file>` - To find out the file.
    
*   `find <file/folder-name>` - Find a file/folder.
    
*   `find <dir-name>` - Find files inside the dir
    
*   `find .-type d` - Show only dir.
    
    *   `.-type f` -Show only files.
        
    *   `.-type f -name "*.txt"` - Show only files with that specific name.
        
    *   `.-type f -iname "*.txt"` - Show only files with that specific name - not case sensitive (i)
        
    *   `.-type f -mmin -20` - Show files which modify less than 20 min ago.
        
    *   `.-type f -mmin +20` - show files which modify more than 20 min ago.
        
    *   `.-type f -maxdepth 2` - Will only show 1 folder deep.
        
    *   `.-size +1k` - will only show files/folders with a size of 1kb
        

## File Compression and Archival

Let's first see how we can check the size of a file in Linux. So `du` the command which stands for Disk usage is a popular command to inspect the size of the file.

`du -sk file.img` Show the size of a file in KB.

`du -sh file.img` Show the size of a file in MB.

`tar` is used to group multiple files or directories into a single file, useful for archiving data. A file created with the `tar` is often called a tarball.

```bash
[~]$ tar -cf hello.tar file1 file2 file3
```

`-cf` a flag is used to create a file with the extension tar.

`tar -tf hello.tar` a command used to check the content of the tarball.

`tar -xf hello.tar` a command used to extract information from a tarball.

Now let's talk about Compression. Compression is a technique used to reduce the size consumed by a file or a data set. So, there are commands which are specifically used for compression. There are 3 ways to compress files i.e,

`bzip2 file.txt`

`gzip file.txt`

`xz file.txt`

And if you want to uncompress files then again we have 3 ways to do that i.e,

`bunzip2 file.txt`

`gunzip file.txt`

`unxz file.txt`

## Searching for Files

Let us suppose that you are the administrator of the Linux system, there would be a situation where you have to locate a file or a directory in the file system. So there are many ways to do that.

Suppose you want to find the file with the name "index.txt". The easiest way to do this is to make use of the `locate` command.

```bash
[~]$ locate index.txt
/home/vamshi/India/mumbai/index.txt
```

Another way to do this is to make use of the find command. Use the `locate` command followed by the directory under which you want to search.

```bash
[~]$ find /home/vamshi -name index.txt
/home/vamshi/India/mumbai/index.txt
```

To search for a file by name, use the `-name` flag, followed by the name of the file.

### grep Command

To search within files, the most popular command in Linux is `grep`.Grep is commonly used to print lines of a file matching a pattern, but it offers a variety of other options as well.

```bash
[~]$ cat file.txt
My name is Vamshi Reddy
I live in Hyderabad
```

```bash
[~]$ grep Hyderabad file.txt
I live in Hyderabad 
```
