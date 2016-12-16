# <img src="https://tuanthong138.files.wordpress.com/2016/10/html_css.jpg" height="200"></br>
Commandline and HTML + CSS Basics!

### Objectives

*After this lesson, students will be able to:

- Navigate through their operating system through terminal
- Create files and folders from terminal
- Delete files and folders from terminal
- Create an HTML file with some HTML elements

### Making files and folders from the command line (10 mins) 

For most people, we create files from our programs that we run on our computers (microsoft word, excel, powerpoint) and we create folders to organize our files. But today, we will learn how to do these things in the terminal.

<img src="http://blog.teamtreehouse.com/wp-content/uploads/2012/09/Screen-Shot-2012-09-25-at-12.57.19-PM.png" height="200">

To open our terminal do the below:

- Lets hit <kbd>command</kbd> + <kbd>space</kbd> together to open our 
- Type in "terminal" in our searchbar and open up that application
- A terminal like the one above should appear!

Althoguh there are multiple ways to open our terminal, we'll stick to this one as I believe it is quick, efficient, and by default all macs should come with this function. 

By default, the terminal should say last login and give the name of the user you are currently logged in as. If it doesn't, don't sweat it for now as we can change that later. 

---
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

#If you get something along those lines give me an IRL thumbs up!#

**Moving on, let's create the folder for our first HTML file!**

In terminal:
```bash
$ mkdir first_folder
$ ls
```

The `mkdir` command Makes a Directory or as we call it, a folder, in the directory we currently are in and gives it whatever name we choose. In this case it is `first_folder`

The `ls` commands lists the contents of the directory we currently are in. In this case, since our current directory is Desktop, it'll list all the files and folders in our current directory. We should see a list of all files and folders printed on the terminal and our folder, `first_folder` should show up!

*If you have a ton of files and folders on your desktop, you may have to scroll through the terminal to see `first_folder`*

---
### Now let's create our HTML file and start writing some HTML! (10 minutes)

Let's go into our first_folder directory like how we did to get into our desktop directory. 

In terminal:
```bash
$ cd first_folder
$ pwd
```

We will `cd` into first_folder from the Desktop directory. I like to use `pwd` whenever I `cd` to confirm I am in the desired directory.

In terminal:
```bash
$ touch index.html
$ ls
```

`touch` is how we create files and similarly to how we named folders, we named our file `index` and used `.html` as the file extention. Like how microsoft word documents are `.doc` or `.docx`, html files are `.html`.

`ls` will again list the files and folders in our current directory, which is now first_folder.

#Give me a thumbs up in slack when you have created your index.html file!#

**Edit our HTML file!**

Now that we have created our HTML file, let's edit it!

In terminal:
```bash
$ sublime .
```

`sublime .` will open all files with certain file extentions in the current  directory in `Sublime Text Editor`. You can also open `index.html` in your text editor of choice (atom, emacs, etc.).

In Sublime, click on index.html on the left column and we should see a blank sheet. 

Let's set up our html file by typing html in our text editor and then pressing tab. We should now see something like this in our text editor: 

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>

</body>
</html>
```

This is pretty much how we will set up the skeleton of an HTML file for the remainder of the course. 
