<h1><ins>Linux Fundamental Part 3</ins></h1><br><br>

<h2><ins>Task 2:Deploy Your Linux Machine</ins></h2>
Connect to TryHackMe Linux Machine with SSH <br>
Command <b>"ssh tryhackme@The IP Address of machine you started"</b>
<img src=https://user-images.githubusercontent.com/78288358/165920573-580fe016-9e3e-4bbb-8fab-8fea163aa387.png style="width:50%; height:50%;"><br>
Example based on mine, follow the ip address of the machine you started, <br>
so mine one will be <b>"ssh tryhackme@10.10.47.55"</b>
<img src=https://user-images.githubusercontent.com/78288358/165921150-f4d46023-37fe-4e5b-9bb7-26b8fb961048.png style="width:50%; height:50%;">
Connected successfully,
<img src=https://user-images.githubusercontent.com/78288358/165921608-7b0bb6dc-9c3d-4bf7-a84b-15408e03ebda.png style="width:50%; height:50%;"><br><br>

<h2><ins>Task 3:Terminal Text Editors</ins></h2>
1. <b>touch</b> is one of the options of create the file, we may create a new file with <b>nano</b> as well.<br>
Command will be <b>nano "file name"</b>, you might see there is a space for you to enter your content after you enter the command<br>
You may add your content in and followed by pressing your keyboard <b>CTRL+X</b> then <b>Enter</b>, it will create a file succesfully after that.
<img src=https://user-images.githubusercontent.com/78288358/165922198-2562107e-c39f-4a13-b51b-71f2305e626a.png style="width:50%; height:50%;"><br><br>
2. <b>nano "file name"</b> can used to edit the existing content of a existing file.<br>
<img src=https://user-images.githubusercontent.com/78288358/165922777-da52737f-4253-4322-bf77-470c9ed20559.png style="width:50%; height:50%;">
<img src=https://user-images.githubusercontent.com/78288358/165922844-f24a83bc-b1a7-4d8b-bcac-d0affd030196.png style="width:50%; height:50%;"><br><br>
Answer: THM{TEXT_EDITORS}<br><br><br>


<h2><ins>Task 4:General/Useful Utilities</ins></h2>
2. On this section, you need to open two terminals. You may leave your old one open, and start another new terminal.<br>
Firstly, you need to type the command <b>"python3 -m http.server"</b> on your tryhackme user terminal.<br> (It starts up a web server) <br>
After that, you may use your new opened terminal to type in command <br><b>"wget http://"IP ADDRESS OF YOUR TRYHACKME MACHINE"/"FILE THAT EXIST ON THAT TRYHACKME MACHINE" to download the file into your own device. </b><br>
In my steps,<br>
You need to have 2 terminals, one is tryhackme another one is root or other user
<img src=https://user-images.githubusercontent.com/78288358/165924963-dc1e8d0e-1fd6-47e4-ba23-bdd5aaa52255.png style="width:50%; height:50%;">
Open your tryhackme terminal and type in the command
<img src=https://user-images.githubusercontent.com/78288358/165925097-002f24ab-15f7-4745-8b6a-089b0127fd62.png style="width:50%; height:50%;">
Open your other user's terminal and type in command to download the file (Please follow yours tryhackme machine's IP address)
<img src=https://user-images.githubusercontent.com/78288358/165925318-51c4710c-e7bc-4ed5-9fd6-361aafa84234.png style="width:50%; height:50%;">
The file had been download and you may view the file with <b>cat</b> command.
<img src=https://user-images.githubusercontent.com/78288358/165925718-1bd508a9-04a6-4002-87ab-4c33de5810a3.png style="width:50%; height:50%;">
3. Answer: THM{WGET_WEBSERVER} <br>
Extra NOTE: It is not limited to http.server only, you may check out other libraries on python website.<br><br><br>



<h2><ins>Task 5:Processes 101</ins></h2>
Remember to read all the guide & instructions above first!<br>
2. There won't be any duplicated or same PID in the process. It will increase by 1 based on previous number if a new process had been created.<br>
Answer: 301 <br><br>
3. <b>"SIGTERM"</b> signal is used to kill a process with a clearning before the process had been killed.<br>
Answer : SIGTERM<br><br>
4. With the <b>"ps"</b> command does not show full processes.<br>
To show the all processes, <b>"ps aux"</b> command is used.
<img src=https://user-images.githubusercontent.com/78288358/165927983-e7dc452f-bb8d-4a22-8178-9f981d574688.png style="width:50%; height:50%;"><br>
Answer: THM{PROCESSES} <br><br>
5. <b>"systemctl stop "service name"</b> to stop the service. (NOT KILLING THE SERVICE)
<img src=https://user-images.githubusercontent.com/78288358/165928617-279147e7-0dba-41c1-ac48-2771fc3577ba.png style="width:50%; height:50%;"><br>
Answer: systemctl stop myservice <br><br>
Extra NOTE: you may type in command <b>"systemctl"</b> to show all services.<br><br>
6. <b>"systemctl enable "service name"</b> to start the service again.<br><br>
Answer: systemctl enable myservice <br><br>
7. <b>"fg"</b> command to bring a background process to foreground.<br><br>
Answer: fg <br><br><br>


<h2><ins>Task 6:Maintaining Your System: Automation</ins></h2><br>
2. <b>"crontab -e"</b> to view the cron file. This question might be very confusing but when you try to read the cron file, <b>@reboot</b> is shown<br><br>
Answer: @reboot <br><br><br>

<h2><ins>Task 7:Maintaining Your System: Package Management</ins></h2>
<h2><ins>Task 8:Maintaining Your System: Logs</ins></h2>

