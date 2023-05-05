# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Practice in the Terminal

[The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)

- A command line, or terminal, is a text based interface to a system.  It allows users to input commands by typing them directly into the terminal and gives feedback. Windows has a default terminal that can be pulled up, but for using Ubuntu, I have it embedded into my power shell for more customization options. 

[Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)

- There are multiple ways to navigate through a terminal. The most common ones are by establishing where you are with pwd (print working directory), we can cd into other files/folders, we can backtrack by utilizing .. notation, the ~ is the shortcut to the home directory, ls can be used to list the contents of a directory.  There are two paths available when navigating which are the relative and absolute path.  The relative is the location relative to where we CURRENTLY are in the file system.  The absolute is the location in relation to the ROOT of the file system.

[More About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

- In Linux everything under the hood is considered to actually be a file.  Characteristics of files can be seen by the characters at the end of a file name such as exe(executable),txt(text),png/gif/jpg(image). File names can exist with spaces but not advisable.  If you need to navigate into a file with spaces you can wrap the name in :'file name': or you can utilize the \ to escape characters :file\ name:. If you need to see all files even hidden ones you can utilize the ls command with a -a added, ls -a.

[Manual Pages](https://ryanstutorials.net/linuxtutorial/manual.php)

- There are tricks on how to navigate around and view information from within the terminal that can be found within the manual.  Some of those commands consist of man <command> which is how you look up the manual page for a SPECIFIC command. man -k <search term> is a keyword search for ALL MANUAL PAGES containing the given search term. The /<term> within a manual page to perform a search for 'term'.  You can press n while performing a search within a manual page to select the next found item.

[File Manipulation](https://ryanstutorials.net/linuxtutorial/filemanipulation.php)

- To create a new file/directory in the terminal we can utilize the mkdir command followed by a file name, mkdir newFile. We can delete this by utilizing the rmdir command. We can create files by using the touch command within the newly created directories. We can then copy those files using the cp command, this command can be used to copy a file into a new destination as well, cp newFile existingPlace. Files or directories can be moved using the mv command, mv option (source)(destination). Mv command also allows us to rename files as we are moving them. The rm command can allow users to remove files and non empty directories, rm fileName. Rm can be dangerous to use at the start of learning, especially in combination with force -f.

[Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)