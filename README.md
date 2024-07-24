# SQL Injection(Login Form)

SQL Injection

In this section, I will explain what SQL injection is, describe some common examples, explain how to find and
exploit various kinds of SQL injection vulnarabilities, and show you how to prevent SQL injections.

what is an SQL Injection?

SQL injection is a vulnarability that allows an attacker to interfere and disrupt queries within a database.
This usally alllows the attacker to veiw data they normally would not be able to see. This data that the
attacker can see now is compromised because they can now make changes to the application that can disrupt the 
applications behavior.


![image](https://github.com/user-attachments/assets/b231c557-c130-4453-9493-9628eb23981b)



Example Description: 

In this example I will be showing you how an SQL injection works and showing you how to
use a SQL.txt file to attack a web application Login page. As you can see down below there are two
application images the foxy proxy applications allows me to listen to the port of the web server and be able to 
see the traffic from there. Burpsuite is an application that works with foxy proxy that allows us to see the web tarffic
within the web browser. I am using OWASP(Open WEb Application secuirty Project) for this example. On the site
there is a vulnarable web application wich is bWAPP. That will be where I am showing how to do this.

Here are links for setting up virtual box and the 2 application(burpsuite, foxy proxy)...

https://www.youtube.com/watch?v=jHGNLvSpaLs

https://www.youtube.com/watch?v=pfaa9YDypJc&t=315s

https://www.youtube.com/watch?v=sBzL_zoYt6o





![image](https://github.com/user-attachments/assets/cbdcad07-4f92-4c95-aa0a-59cfaeb4f5c3)





![image](https://github.com/user-attachments/assets/9e6f93ad-f3c5-4000-8540-6aca63e8f6ae)


![image](https://github.com/user-attachments/assets/7f323317-8270-4101-ba43-dc3ee530d0e3)




SQL Injection Example:


Step 1. 


Create an account with bWAPP then click the tab that says choose your bug. After doing that clcick on
the tab that says SQL Injection(Login Form). 


![image](https://github.com/user-attachments/assets/c0088d2f-ee44-41e2-8bb0-f800bd1a93fc)










