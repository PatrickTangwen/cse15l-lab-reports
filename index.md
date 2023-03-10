# CSE15L Lab1 Tutorial
**Welcome to the tutorial page! 
<br>
<br>
In this page,you will know how to install the VS Code, connect the remote server,and try typing some commands.**

***Step 1 (Installing VScode)***
* Click VScode website: [VScode](https://code.visualstudio.com/)
* Please read the instructions on the website carefully and download the VScode according to your operation system
* When it is downloaded, install the package and open the VScode icon, you should be able to see a VScode window like this:
![Image](https://raw.githubusercontent.com/PatrickTangwen/Markdown/main/images/WechatIMG145.png)

***Step 2 (Remotely Connecting)***
* In your VScode, open the terminal by clicking the **Terminal** → **New Terminal** (both button can found on the menu)<br>
You should be able to see the terminal windows like this:
![terminal](https://raw.githubusercontent.com/PatrickTangwen/Markdown/main/images/WechatIMG144.png)<br>

If you are using Windows, you need to install `git` first. Here is the link: [git](https://gitforwindows.org/)<br>

* In the terminal window: type the following<br>

`$ ssh cs15lwi23zz@ieng6.ucsd.edu`<br>
(don't include `$` in your terminal, it is just a symbol to imply that this is a command line) <br>

**NOTICE:** To login with your own course specific accoutn, you should replace the `zz` by the letters from you own specific cse15l account.<br>

If this is your first time to login the remote server, you will probably see the following responses from terminal:<br>
```
⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```

Go head,type `yes` in the terminal and then press enter. Then,the terminal will ask you to type your password by giving a password prompt. So,just type your password in the prompt. Then,it will gives the response like this:
```
Last login: Sat May 28 11:28:18 2022 from c-24-130-138-6.hsd1.ca.comcast.net
Hello cs15lwi23akw, you are currently logged into ieng6-201.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   20:00:01   14  0.34,  0.16,  0.15
ieng6-202   20:00:01   9   0.59,  0.19,  0.17
ieng6-203   20:00:01   3   0.00,  0.03,  0.08

 
Fri Jan 13, 2023  8:02pm - Prepping cs15lwi23
```
When you see the interaction like this, congratulations! Your terminal is now connected a computer in the CSE basement! In this context, your own computer is called *client* and the computer in the cse basement is called *server*.

***Step 3 (Trying Some Commands)*** <br>
In this section, trying to type some commands on your terminal to see some interesting output.
For example, when I run commands like `ls ~lat`, I got the following:
![terminal](https://raw.githubusercontent.com/PatrickTangwen/Markdown/main/images/WechatIMG143.png)
<br>
Here are some commands you may try:
* `pwd`
* `cat /home/linux/ieng6/cs15lwi23/public/hello.txt` 

When I typed command like `pwd`, it gave the following:

```
[cs15lwi23akw@ieng6-201]:~:32$ pwd
/home/linux/ieng6/cs15lwi23/cs15lwi23akw
```

From above, `pwd` tells me which directory I'm currently working with. It helps me to know the path. <br>

When I typed command `cat /home/linux/ieng6/cs15lwi23/public/hello.txt`, it gave the following:
```
[cs15lwi23akw@ieng6-201]:~:37$ cat /home/linux/ieng6/cs15lwi23/public/hello.txt
Hello! Welcome to CSE 15L
```
From above, `cat` will print the content of given paths. Here, the path refers to `/home/linux/ieng6/cs15lwi23/public/`<br>
The content in `hello.txt` is the "Hello! Welcome to CSE 15L".<br>
Thus,if you want to print the content of a file, just use `cat` + your file path. 



***Congratulations!*** 
<br>
You've completed the cse15l lab tutorial !






