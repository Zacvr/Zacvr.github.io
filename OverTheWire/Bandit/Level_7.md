---
layout: page
title: Bandit Level 7
permalink: /Tutorials/OTWBandit/Level_7/
---
[OverTheWire-Level Directory](https://zacvr.github.io/Tutorials/OTWBandit/)
<br/>
[Previous Level: 6](https://zacvr.github.io//Tutorials/OTWBandit/Level_6)
<br/>

Level 7 Fight!
<br/><br/>
In order to begin you will need to use PuTTY or preferably Linux and use the following information
<br/><br/>
If you are currently in a level type "logout"
<br/><br/>
Now type "ssh bandit7@bandit.labs.overthewire.org -p 2220"
<br/>
Password:"HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs"
<br/>
We are now into level 7
<br/><br/>
For this level we are told
<br/><br/>
"The password for the next level is stored in the file data.txt next to the word millionth"
<br/><br/>
If you have done this before you will know you can use
<br/><br/>
"ls " to show files/folders
<br/><br/>
We then see"data.txt"
<br/><br/>
To find the password we will need to find the correct part of the txt file with
<br/><br/>
"grep millionth data.txt"
<br/><br/>
This will show "millionth       cvX2JJa4CFALtqS87jk27qwqGhBM9plV" as a suspect
<br/><br/>
The password seems to already be shown!
<br/><br/>
"cvX2JJa4CFALtqS87jk27qwqGhBM9plV"
<br/><br/>
Once again we can use
<br/>
"ssh bandit8@bandit.labs.overthewire.org -p 2220"
<br/>
and the password we just found to login to the next level
<br/><br/>
[Next Level: 8](https://zacvr.github.io//Tutorials/OTWBandit/Level_8)
