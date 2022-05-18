<h1><ins>Introduction to Offensive Security</ins></h1>
<h2><ins>Task 1:Hacking your first machine</ins></h2>
Startup the machine and open the terminal(Linux Environment)<br><br>
In this lesson, we know about there are many directories in a website. Some website are shown and you can redirect from, but there are hidden webpage, so there might be a vulnerability on that hidden webpage.<br>
We will be using gobuster here. It is a web directory enumeration tool used to list out all the directories of a web.<br>
Go the terminal and type down "gobuster --help" for a list of available commands<br><br>
1. Go to terminal and type down the command <b>"gobuster -u http://fakebank.com -w wordlist.txt"</b><br>
You will see image as below, there are two directories found(/images & /bank-transfer)<br>
<img src=https://user-images.githubusercontent.com/78288358/169036026-69933a1e-27f4-4148-a80f-3c6b736ecafb.png style="width:50%; height:50%">

We can try to redirect to both URL and see what inside that directory.<br>
<img src=https://user-images.githubusercontent.com/78288358/169035983-ec14f9d1-0dc8-4b03-b3d8-c409ca289cab.png style="width:50%; height:50%">
Now we can start to hack the bank.
<img src=https://user-images.githubusercontent.com/78288358/169036250-2768e01a-1293-4d1d-b468-141b8c1c3314.png style="width:50%; height:50%"><br>
<img src=https://user-images.githubusercontent.com/78288358/169036284-01c0e59b-26a0-4a07-935e-b47118afdacc.png style="width:50%: height:50%"><br>
<img src=https://user-images.githubusercontent.com/78288358/169036382-929eb12f-65e8-4ba0-b3f1-e93c55f0d722.png style="width:50%; height:50%">
Now go back to the www.fakebank.com and check out the content(what had appeared and what had changed).<br><br>
Answer: BANK-HACKED<br><br><br>


<h2><ins>Task 2:What is Offensive Security?</ins></h2>
