# Bandit

The Bandit wargame from OverTheWire is aimed at absolute beginners.
<br>
It is a game you connect to through SSH that will help you improve your command line skills, your Linux skills, and your hacker skills.

If you are following along with the game yourself, you may encounter many situations in which you have no idea what you are supposed to do. There are several things you can try when you are unsure how to continue in the game (before watching the solution).
<br>

First, if you know a command, but don’t know how to use it, try the manual (man page) by entering man <command>. For example, man ls to learn about the “ls” command. The “man” command also has a manual, try it! When using man, press q to quit (you can also use / and n and N to search).
<br>

Second, if there is no man page, the command might be a shell built-in. In that case, use the help <X> command. For example, help cd.
<br>

You can find instructions for the game here: https://overthewire.org/wargames/bandit/

# How to begin

Host: bandit.labs.overthewire.org
<br>
Port: 2220
<br>
``` 
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
Here we can change 'bandit0' to any Bandit level we want to access.
<br>
The password asked at a particular level is the password that we get in its previous level.
<br>
For level 0 it is bandit0, for example.
