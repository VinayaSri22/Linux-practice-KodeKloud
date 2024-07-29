**Question:**
In response to heightened security concerns, the `xFusionCorp` Industries security team has opted for custom Apache users for their web applications. Each user is tailored specifically for an application, enhancing security measures. 
Your task is to create a custom Apache user according to the outlined specifications:

  a. Create a user named john on App server 2 within the Stratos Datacenter.
  b. Assign a unique UID 1580 and designate the home directory as /var/www/john.

**Server LogIn Credentials**

> https://www.nbtechsupport.co.in/2022/08/kodekloud-servers-login-credentials.html

**Solution:**

1. ssh steve@stapp02
2. sudo -u
3. useradd -u 1580 john
4. id john
5. cat /etc/passwd | grep john
6. usermod -d /var/www/john -m john
7. cat /etc/passwd | grep john
