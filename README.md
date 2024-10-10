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
cp directory0/file directory1
```

11  moves file from one directory to another directory

```bash
mv directory0/file directory1
```

**the `mv` command can also be used in a different way , suppose in a directory a code is named as reverse_arr.java i want to rename the code file as reverse.java , then type `mv reverse_arr.java reverse.java`**

12  prints the contents of a file in text form in terminal 

```bash
cat array.java
```






