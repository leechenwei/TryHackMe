https://tryhackme.com/room/linuxfundamentalspart2<br>
<h1><ins>Linux Fundamental Part 2</ins></h1><br><br>

<h2><ins>Task 2:Accessing Your Linux Machine Using SSH (Deploy)</ins></h2><br>
You may connect to the tryhackme machine using SSH(Secure Shell) <br>
SSH is a network communication protocol used for two systems to communicate between each other. <br><br><br>
<h2><ins>Task 3:Introduction to Flags and Switches</ins></h2><br>
2. Keyboard <b>DOWN</b> to scroll or navigate the manual pages. <br><br>
Answer: down <br><br>
3. To display the output in human-readable display can be done by doing <b>-help</b><br><br>
Answer: -h <br><br><br>
<h2><ins>Task 4:Filesystem Interaction Continued</ins></h2><br>
1. <b>touch "file name"</b> to create the file on the current directory.<br><br>
Answer: touch newnote <br><br><br>
2. <b>file "file name"</b> to check the file type <br>
<img src=https://user-images.githubusercontent.com/78288358/165662539-d8c70226-95bd-442d-8894-00749fd4cb3c.png style="width:50%; height:50%;">
Answer: ASCII text <br><br>
3. <b> mv "file to move" "move location"</b> to move the file from one file to another file.
<img src=https://user-images.githubusercontent.com/78288358/165662752-f4aada54-18ff-476a-b811-8c13f3fa456c.png style="width:50%; height:50%;">
Answer: mv myfile myfolder <br><br>
4. <b>cat "file"</b> to view content.
<img src=https://user-images.githubusercontent.com/78288358/165662919-18564118-38e3-499a-96ac-5a3fc3aa483f.png style="width:50%; height:50%;">
Answer: THM{FILESYSTEM}

<h2><ins>Task 5:Permissions 101</ins></h2><br>
1. <b>cat "file"</b> can know the content of file might lead to know who is the author of the file.
<img src=https://user-images.githubusercontent.com/78288358/165663952-c74a3653-bef4-484a-adb6-7d6eca60c519.png style="width:50%; height:50%;">
Answer: user2 <br><br>
2. <b>su "user" OR sudo "user"</b> to switch to that user.
<img src=https://user-images.githubusercontent.com/78288358/165664210-7fa25eb3-0215-4e80-8510-ac51375df90c.png style="width:50%; height:50%;">
Answer: su user2 <br><br>
4. <b>cat "file"</b> read the file (similar to first question)
<img src=https://user-images.githubusercontent.com/78288358/165664420-f2171772-f22a-47d9-9921-0904c86f0603.png style="width:50%; height:50%;">
Answer: THM{SU_USER2} <br><br><br>

<h2><ins>Task 6:Common Directories</ins></h2><br>
2. <b>cd /var/log OR cat /var/log</b> to view the log file on Linux system.<br><br>
Answer: /var/log <br><br>
3. <b>/tmp</b> is the directory of the temporary file, it store a file for a short period of time, worked like a RAM<br><br>
Answer: /tmp <br><br>
4. <b>/root</b> will be home directory of the root user for most cases, for example <b>user2</b> will be the home directory of the user2<br><br>
Answer: /root <br><br><br>


<h2><ins>Proceed to Linux Fundamental Part 3</ins></h2>


