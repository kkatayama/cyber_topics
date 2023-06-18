# Week 6 Assignment

#### 1. What does OWASP stand for?
<br>

-

#### 2. What are the OWASP Top 10?
<br>

-
-

#### 3. Using the OWASP Juice-Shop website we ran in class, determine the password for the user `jim@juice-sh.op`.

<br>

-


> Some tips to get you started!

##### a) Download the password list.

```bash
wget https://raw.githubusercontent.com/kkatayama/cyber_topics/master/passwords.txt
```
##### b) Start the Docker Service.  

```bash
systemctl start docker
```
##### c) Open OWASP Zed Attack Proxy

```bash
owasp-zap
```

<br>

##### d) Open Firefox.  

```bash
firefox
```
##### e) Navigate to the login page.  
<https://kali:3000/#/login>
> If you do not see a place to enter a `Email` and `Password` then you may still be logged in.
> Click `Account` > `Log Out` to log out.

##### f) Use the password list you just downloaded to `fuzz` the password

<br>


If you are having trouble completing this task, you may find the `md5 hash` password for `Jim's` account in the lecture notes...