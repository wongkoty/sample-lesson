# <img src="https://tuanthong138.files.wordpress.com/2016/10/html_css.jpg" height="200"></br>
Commandline and HTML + CSS Basics!

### Objectives

*After this lesson, students will be able to:

- Navigate through their operating system through terminal
- Create files and folders from terminal
- Delete files and folders from terminal
- Create an HTML file with some HTML elements
- Link a HTML file to a CSS file

### Making files and folders from the command line 

For most people, we create files from our programs that we run on our computers (microsoft word, excel, powerpoint) and we create folders to organize our files. But today, we will learn how to do these things in the terminal.

<img src="http://blog.teamtreehouse.com/wp-content/uploads/2012/09/Screen-Shot-2012-09-25-at-12.57.19-PM.png" height="200">

To open our terminal do the below:

- Lets hit <kbd>command</kbd> + <kbd>space</kbd> together to open our 
- Type in "terminal" in our searchbar and open up that application
- A terminal like the one above should appear!

Althoguh there are multiple ways to open our terminal, we'll stick to this one as I believe it is quick, efficient, and by default all macs should come with this function. 

By default, the terminal should say last login and give the name of the user you are currently logged in as. If it doesn't, don't sweat it for now as we can change that later. 

### Let's go into our desktop and create a folder!

In our terminal type:
```bash 
$ pwd
```

`pwd` should Print Working Directory, which means it is the current directory that we are in. 

Next lets go into our desktop.

In terminal type:
```bash
$ cd Desktop
```

`cd` should allow us to Change Directory to the one we specfied, which was Desktop.

Now `pwd` in terminal again and it should display something along the lines of:
`/Users/some_user/Desktop/` 

If you get something along those lines give me a thumbs up!

Moving on, let's create the folder for our first HTML file!

In terminal:
```bash
$ mkdir first_folder
$ ls
```

The `mkdir` command Makes a Directory or as we call it, a folder, in the directory we currently are in and gives it whatever name we choose. In this case it is `first_folder`

The `ls` commands lists the contents of the directory we currently are in. In this case, since our current directory is Desktop, it'll list all the files and folders in our current directory. 



