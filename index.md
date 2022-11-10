# Week 7 Lab Report: Vim

---

# Student: ***[Ben Stirling](https://github.com/abenstirling)***
# Professor: ***[Joe Politz](https://github.com/jpolitz)***
# Date: ***9/29/22***

---

In this lab, we will be exploring the wonders of software development with the supreme tool: Vim. 

---

## Part 1

---

For the part, I chose to change the name of all of the `start` syntax to `base` in the `[DocSearchServer.java](http://DocSearchServer.java)` file. 

First, I entered the terminal and wrote the following: 

```bash
vim DocSearchServer.java
```

Now I have entered the Vim editor for the file I want to edit. 

![Untitled](Week%207%20Lab%20Report%20Vim%2028685867ab20403da3582d6087e8550b/Untitled.png)

---

I entered the following comands, which searched and brought me to the first start then I pressed C and E to highlight and delete the first `start` . 

```bash
/start
c
e
```

![Untitled](Week%207%20Lab%20Report%20Vim%2028685867ab20403da3582d6087e8550b/Untitled%201.png)

In order to move on, I typed in base and hit escape to go back to the normal mode. 

```bash
base
*esc*
```

I repeated the steps of:

```bash
/start
c
e
base
*esc*
```

Until I reached the following message, which indicated that I had already replaced all of the terms that I wanted. 

![Untitled](Week%207%20Lab%20Report%20Vim%2028685867ab20403da3582d6087e8550b/Untitled%202.png)

As usual, I entered the following to save and quit: 

```bash
: 
:q
```

![Untitled](Week%207%20Lab%20Report%20Vim%2028685867ab20403da3582d6087e8550b/Untitled%203.png)

We have successfully changed all of the terms that we were looking for in Vim!

---

## Part 2

---

For the second part of this lab, we were tasked to do:

- Start in Visual Studio Code and make the edit there, then `scp` the file to the remote server and run it there to confirm it works (you can just run `bash test.sh` on the remote to test it out). Consider having the appropriate `scp` command in your command history or easily copy-pasteable!
- Start already logged into a `ssh` session. Then, make the edit for the task you chose in Vim, then exit Vim and run `bash test.sh`.

Here are my times for the first and second task respectively: 

1. 3m:15s
2. 1m:23s

Clearly, I am much more efficient with Vim and the second option. It is good to know that I am capable of performing both types of operations because I will likely have to do both in the future. 

If I were to work on a program that I am running remotely, I would likely chose the Vim option because I have worked on RaspberryPi servers and it is much more convenient to work directly on the remote computer because you can edit and run in one go. 

Also, I am not really a fan of the `scp` command because I always find it difficult to transport it to the correct location on the first try. The `scp` command does have merit because I could have a large file that I don’t want to write or edit on the remote computer, so it would make sense to just transport it and/or edit it on the local desktop and move over the changes. 

---

This was one of my favorite labs because I got to exercise and test my Vim skills.

It was great to see the types of workflows and how efficient I am and can be if I dial down the commands and minimize my own errors. 

Vim is a really powerful tool that can allow me to edit almost as fast as I think, so I will be using it with every project from now on!