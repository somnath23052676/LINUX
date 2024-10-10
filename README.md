# LINUX
commands of linux terminal and bash scripting

here in this repository , i will introduce some basic commands i have learnt while using linux distro , I have learnt linux from various sources inlcuding youtube and books which include the linux commandline , shell scripting bible 

## BASIC COMMANDS



### FILE HANDLING

1  create a drectory

```bash
mkdir directoryname
```
2  changes directory to the specifid directory

```bash
cd directoryname
```
3  exits from the current directory

```bash 
cd ..
``` 
**you can add more . after cd .. then one level more exit will be done , for example you are in /java/algorithms/sliding_windows , you want to go to /java then type cd ... , if you completely go back to home directory then cd ....**

 4  removes an non empty directory 

```bash
rm -r directoryname
```

5  lists directories and files 

```bash
ls
```

6  lists directories and files with more detail informations

```bash
ls -l
```

7 all directores and files including hidden directories and files

```bash
ls -a
```

8 all directores and files including hidden directories and files with detailed information

```bash
ll -a
```
or
```bash
ls -a -l
```

9  shows current directory directory

```bash
pwd
```

**full form is print working directory**

10  copies file from one directory to another directory

```bash
cp directory_0/file directory_1
```

11  moves file from one directory to another directory

```bash
mv directory_0/file directory_1
```

**the `mv` command can also be used in a different way , suppose in a directory a code is named as reverse_arr.java i want to rename the code file as reverse.java , then type `mv reverse_arr.java reverse.java`**

12  prints the contents of a file in text form in terminal 

```bash
cat array.java
```

13 prints the contents of a file in text form in terminal - colourful 

```bash
lolcat array.java
```

**lolcat is not preinstalled in most linux distibutions , download with  the following command**

```bash
sudo apt install lolcat
```

14 changing directory from another directory

**if you are in a directory and want to go to another directory and dont want to change the directory using `cd ..` then `cd directory_name` , then this command is useful**

```bash
cd /home/user_name/drectory_name
```

### SUDO COMMANDS

sudo means super user do , this command allows a user to execute a command as superuseer 

1 installing packages

for installing packages different linux distributions use different packages , some of the popular packages are
apt - adanced packaging tool
pacman - package manager 
flatpak 
snap 

as I use ubuntu based system pop os , i use apt ,

```bash
sudo apt install package_name
```

2 removing packages

```bash
sudo apt remove package_name
```

3 remove packages and it's configuration files

```bash
sudo apt purge package_name
```

4 remove unused packages

```bash
sudo apt autoremove
```

5 updating system

```bash
sudo apt update
```

6 upgrading system

```bash
sudo apt upgrade
```

7 add new user profile

```bash
sudo adduser username
```

8 delete a user

```bash
sudo deluser username
```

9 show all hardware information

```bash
sudo lshw
```

**this function can also run without sudo**

10 networking restart

```bash
sudo systemctl restartnetworking
```

### GAME COMMANDS

every command has to be first installed with `sudo apt install package_name`

1 cowsay 

this command prints a ascii cow saying something and you can print other things than cow

```bash
sudo apt install cowsay
```
command -
```bash
cowsay " this is a cowsay command "
```
output - 
```

___________________________
< this is a cowsay command  >
 ---------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||

```
command -
```bash
cowsay -f dragon "this is a dragon cowsay command"
```
output -
```

< this is a dragon cowsay command >
 ---------------------------------
      \                    / \  //\
       \    |\___/|      /   \//  \\
            /0  0  \__  /    //  | \ \    
           /     /  \/_/    //   |  \  \  
           @_^_@'/   \/_   //    |   \   \ 
           //_^_/     \/_ //     |    \    \
        ( //) |        \///      |     \     \
      ( / /) _|_ /   )  //       |      \     _\
    ( // /) '/,_ _ _/  ( ; -.    |    _ _\.-~        .-~~~^-.
  (( / / )) ,-{        _      `-.|.-~-.           .~         `.
 (( // / ))  '/\      /                 ~-. _ .-~      .-~^-.  \
 (( /// ))      `.   {            }                   /      \  \
  (( / ))     .----~-.\        \-'                 .~         \  `. \^-.
             ///.----..>        \             _ -~             `.  ^-`  ^-_
               ///-._ _ _ _ _ _ _}^ - - - - ~                     ~-- ,.-~
                                                                  /.-~


```
command -
```bash
cowsay -f tux "this is a linux penguin cowsay command "
```
output -
```
_________________________________________
< this is a linux penguin cowsay command  >
 -----------------------------------------
   \
    \
        .--.
       |o_o |
       |:_/ |
      //   \ \
     (|     | )
    /'\_   _/`\
    \___)=(___/

```


2 cmatrix 

this command prints a matrix

```bash
sudo apt install cmatrix
```
to execute cmatrix -

```bash
cmatrix
```

by default the colout of cmatrix is green to specify colour -

```bash
cmatrix -C colour
```
**Valid colors are green, red, blue, white, yellow, cyan, magenta and black.**

there are a lot of cmatrix functions , to know all of them , type the following command
```bash
cmatrix --help
```







