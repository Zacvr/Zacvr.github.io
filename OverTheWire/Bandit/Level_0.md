---
layout: page
title: Bandit Level 0
permalink: /Tutorials/OTWBandit/Level_0/
---
[OverTheWire-Level Directory](https://zacvr.github.io/Tutorials/OTWBandit/)
<br/>
Level 0 Fight!


In order to begin you will need to use PuTTY or preferably Linux and use the following information

SSH Info
Host: bandit.labs.overthewire.org
Port: 2220

Username:bandit0 
Password:bandit0

I use this specific line to type in each level 
"ssh bandit0@bandit.labs.overthewire.org -p 2220" 
Then just change the 0 for the level you want to type the password to
Then use the password:bandit0

Now we are into level 0

If you us "ls" you will see a file named "readme"
If you use "cat readme" you will get the password 
"boJ9jbbUNNfktd78OOpsqOltutMc3MY1"

then you can type in

ssh bandit1@bandit.labs.overthewire.org -p 2220
and the password we just found to login to the next level
<br/>
[Next Level: 1](https://zacvr.github.io//Tutorials/OTWBandit/Level_1)