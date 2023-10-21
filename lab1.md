## CSE15L Lab Report 1

![Image](corgi.jpg)

---

# **cd Command**
---

#### **1.** Share an example of using the command with no arguments.
   
If I used the change directory command with no arguments in the terminal then it will take me back to the home directory. If I ran the command in the home directory then nothing will happen. For example I used `cd` in the terminal and I was in the /home/lecture1/messages directory. After the command ran I did `pwd` and was back in the home directory. 

```
Command: [user@sahara ~]$ cd 
Output: /home
What the working directory was when the command was run: /home/lecture1/messages
```
<!---->

#### **2.** Share an exmaple of using the command with a path to a directory as an argument.

If I used the change directory command with a path as an argument then it will take me to that folder/directory. For example, I used the `cd` command and passed in the lecture1 folder as an arguement. After running the command it has changed my directory to that folder. This is becasue I specified where I wanted to change my directory and I gave a valid path to the command.

```
Command: [user@sahara ~]$ cd lecture1
Output: [user@sahara ~/lecture1]$
What the working directory was when the command was run: /home
```

#### **3.** Share an example of using the command with a path to a file as an argument.

If I were to use the change directory command with a path to a file as an agrument then it will not work (Error). This is becasue a file is not a directory. For example, when I use `cd` on the text file, en-us.txt, the ouput was that en-us.txt is not a directory, that is why I cannot use the `cd` command on it.

```
Command:[user@sahara ~/lecture1/messages]$ cd en-us.txt
Output: bash: cd: en-us.txt: Not a directory
What the working directory was when the command was run: /home/lecture1/messages
```




# **ls Command**
---
#### **1.** Share an example of using the command with no arguments.

If I were to use the `ls` command with no arguements then it will show me a list of files, codes, and subdirectories of the current directory I am in. For example, I used `ls` in the terminal and it outputed lecture1, so that means that I was in the home directory and the list of files/codes/subdirectories in the home directory is lecture1.

```
Command: [user@sahara ~]$ ls
Output: lecture1
What the working directory was when the command was run: /home
```

#### **2.** Share an exmaple of using the command with a path to a directory as an argument.

If I were to use the `ls` command with a path to a directory as an argument then it will show me a list of files, codes and subdirectories in that directory. If I used `ls` on Lecture1 it will give me the files, codes and subdirectories inside of the lecture1 directory, which are Hello.class, Hello.java messages and README.

```
Command:[user@sahara ~]$ ls lecture1
Output: Hello.class  Hello.java  messages  README
What the working directory was when the command was run: /home
```

#### **3.** Share an example of using the command with a path to a file as an argument.

If I used the `ls` command with a path to a file as an argument then it will just output the name of the file. For example, I used `ls` on the text file, en-us.txt, in the terminal and the output was en-us.txt. I beleive I got this output becasue `ls` is used to list the information about the file and in this case it just displayed the name of the file. Another thing that the `ls` command can do is print out the information of an absolute/relative path to a file. For example, if I were to give the `ls` command an absolute path to a file such as, /home/lecture1/messages/en-us.txt then it will print out that absolute path to the file. 

```
Command: [user@sahara ~]$ ls en-us.txt
Output: en-us.txt
What the working directory was when the command was run: /home/lecture1/messages
```
```
Command: [user@sahara ~]$ ls /home/lecture1/messages/en-us.txt
Output: /home/lecture1/messages/en-us.txt
What the working directory was when the command was run: /home/lecture1/messages
```



# **cat Command**
---
#### **1.** Share an example of using the command with no arguments.

When using the `cat` command without any arguments the terminal waited for me provide my own input from the computer. When doing so and clicking the enter key it would output what I have just typed into the terminal.

```
Command:   [user@sahara ~]$ cat
            Hello Vincent
Output: Hello Vincent
What the working directory was when the command was run: /home
```

#### **2.** Share an exmaple of using the command with a path to a directory as an argument.

If I use the command with a path to a directory as an argument then it would spit out that the path was a directory (Error). For example, if I typed in the terminal `cat` lecture1, then it would the output would be `cat`: lecture1: Is a directory. I beleive I got this result because I tried to concatenate and display the contents of a directory and not a file. The `cat` command is trying to display the contents of the directory. 

```
Command:[user@sahara ~]$ cat lecture1
Output: cat: lecture1: Is a directory
What the working directory was when the command was run: /home
```

#### **3.** Share an example of using the command with a path to a file as an argument.

When using the command with a path to a file as an argument after changing into the right directory then it will print out the contents of that file. For example, I am in the directory /home and if I do the command `cat` /home/lecture1/messages/en-us.txt it will print out the content inside that file which is Hello World!

```
Command: [user@sahara ~]$ cat /home/lecture1/messages/en-us.txt
Output: Hello World!
What the working directory was when the command was run: /home
```



