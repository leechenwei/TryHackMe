<h1><ins>Burp Suite: Repeater</ins></h1>
Open the attackbox and open the Burp Suite Community Version. <br>
Try and look and familiar with the Burp Suite's GUI. <br>

<h2><ins>Task 4:Repeater:Views</ins></h2>
<img src=https://user-images.githubusercontent.com/78288358/171150214-0f51b850-986c-4019-8346-ef284cc53e83.png>
2. Answer: Render<br><br><br>

<h2><ins>Task 6:Practical: Example</ins></h2>
Intercept a request to the website and move it to Repeater.<br>
Head toward Repeater and add on <b>"FlagAuthorised: True"</b> and click Send. The response will show on the right side.<br>
Based on the image below, I'm not using the Repeater but I modify the content of request in the proxy intercept session straight<br>
<b>It is recommeded to use Repeater so you can modify as many times as you want without refreshing the web again</b>
<img src=https://user-images.githubusercontent.com/78288358/170943074-71910b82-22ac-4c9b-82f2-98251ef962e6.png style"width:50%; height:50%;">
1. Answer: THM{Yzg2MWI2ZDhlYzdlNGFiZTUzZTIzMzVi}<br><br><br>

<h2><ins>Task 7:Practical: Challenge</ins></h2>
From this, Burp Suite is very good in the use of changing the request content. <br>
From this task, we need to get a 500 Response Error in return. <br>
Firstly, we need to intercept the request that send to /products/3 directory. After that move it to Repeater.<br>
In the repeater, we can change the UID of products to get a 500 Internal Server Error.<br>
500 Internal Server Error is caused by unexpected condition that prevent the server from fulfilling the request.<br>
Modify the UID and click Send. You will receive the 500 Internal Server Error response and look out for flag. <br>
<img src=https://user-images.githubusercontent.com/78288358/170944005-f4480a12-c44a-4937-a1b5-ce6cfd43c236.png>
2. Answer: THM{N2MzMzFhMTA1MmZiYjA2YWQ4M2ZmMzhl}<br><br><br>
<h2><ins>Task 8:SQLi with Repeater</ins></h2>
Advised to read and follow the content provided by THM in this task.<br>
Intercept a request at /about/0 directory and send to Repeater.<br>
Change the UID or PARAMETER to <b>"0 UNION ALL SELECT notes,null,null,null,null FROM people WHERE id = 1"</b> and click Send.<br>
<img src=https://user-images.githubusercontent.com/78288358/170944815-30864630-6692-4c01-950e-f2680e64e625.png>
2. Answer: THM{ZGE3OTUyZGMyMzkwNjJmZjg3Mzk1NjJh}<br><br><br>
<h1>Continue to Passive Reconnaissance</h1>
