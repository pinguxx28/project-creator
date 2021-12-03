# Project-Creater

## About

Project-Creater is, like the name suggests a project creater.
Made by pinguxx28, Dec 2nd - (Dec 3rd, last update)

## How to download

- Download this repository or use `git clone https://github.com/pinguxx28/project-creator.git`
- Open up a bash terminal
- Locate to the directory you cloned into using `cd /[PATH_TO_YOUR_DIR]`
<br>
- Do `pwd` to see in which directory you are currently in, copy the output
- Use your preferred text editor (vim, vs code, sumblime, etc..) to open "mkp" and paste the output inside of the quotation marks ("") and save the file
<br>
- Do `$PATH` to locate the bash commands (this should give you /usr/local/bin)
- Check that you don't have any other file named mkp inside of $PATH with `file [path]/mkp` (if you don't have a file there, the console should output an error, else you need to rename the mkp file (current dir) using the `mv` command or delete the mkp file in $PATH if you don't use it)
<br>
- Do `sudo cp mkp [path]`
- Give premissions to the file, to use it without the `sudo` command with `sudo chmod +x [path]/mkp`
<br>
- Congrats you can now use the `mkp` command in the terminal

## How to use

- Type `mkp` into the terminal
- "location:" where to put the directory e.g ~/Java
- "name:" what to name the directory e.g Snake
- "lang:" what's the file extension the project will use (used for startup like java, py, cs)
- "exc:" what subdirectories do you want to include see more below

### flags/exc/subdirs

s, src
b, bin
l, lib
g, .gitignore
r, README.md
m, mod
p, pkg
f, startup file main.[lang]

### supported languages
```
.bash
.c
.cpp
.cs
.go
.html
.java
.js
.py
```