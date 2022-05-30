<h1><ins>Content Discovery</ins></h1>
<h2><ins>Task 1:What is Content Discovery?</ins></h2>
1. Answer: Manually<br><br><br>
2. Answer: Automated<br><br><br>
3. Answer: OSINT<br><br><br>

<h2><ins>Task 2:Manual Discovery - Robots.txt</ins></h2>
Redirect to the robots.txt URL. and you found there are 3 lines of words. You may notice the there is a directory is disallowed.<br>
<img src=https://user-images.githubusercontent.com/78288358/169673779-e0b59e57-125f-4d5e-8b1a-376be2e469db.png style="width:50%; height:50%">
1. /staff-portal<br><br><br>


<h2><ins>Task 3:Manual Discovery - Favicon</ins></h2>
Type down the command "curl https://static-labs.tryhackme.cloud/sites/favicon/images/favicon.ico | md5sum" in your linux terminal and see what in return.<br>
Based on the output u can identify it on https://wiki.owasp.org/index.php/OWASP_favicon_database to determine which framework that favicon belong to.<br><br>
1. Answer: cgiirc<br><br><br>

<h2><ins>Task 4:Manual Discovery - Sitemap.xml</ins></h2>
Go to the website /sitemap.xml and check out there is a secret directory. <br>
<img src=https://user-images.githubusercontent.com/78288358/169673802-a6c8e1d6-27ee-4383-887c-5da09aace289.png style="width:50%; height:50%;">
1. Answer: /s3cr3t-area <br><br><br>

<h2><ins>Task 5:Manual Discovery - HTTP Headers</ins></h2>
Type down the command "curl http://IP ADDRESS OF YOUR MACHINE -v" to retrieve the flag.<br>
<img src=https://user-images.githubusercontent.com/78288358/169674232-024c5da5-ccc3-4996-b8e3-da68ad675447.png style="width:50%; height:50%;">
1. Answer: THM{HEADER_FLAG}<br><br><br>

<h2><ins>Task 6:Manual Discovery - Framework Stack</ins></h2>
![image](https://user-images.githubusercontent.com/78288358/169674219-0d66e563-9a9e-4122-99c7-8288586cb1d5.png)
![image](https://user-images.githubusercontent.com/78288358/169674223-47aa860c-e3fc-438e-a961-f468372bc82c.png)

<h2><ins>Task 7:OSINT - Google Hacking / Dorking</ins></h2>
<h2><ins>Task 8:OSINT - Wappalyzer</ins></h2>
<h2><ins>Task 9:OSINT - Wayback Machine</ins></h2>
<h2><ins>Task 10:OSINT - GitHub</ins></h2>
<h2><ins>Task 11:OSINT - S3 Buckets</ins></h2>
<h2><ins>Task 12:Automated Discovery</ins></h2>

