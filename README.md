# Payload-Wrapper
A Wrapper for a reverse shell/tcp payload made via msfconsole
In reverse/tcp folder is my code to make a file that creates a reverse shell targeting an IP of the users choosing. 
It uses an nmap scan to find out what operating system the IP is using and once it does it puts together a metesploit path and puts it into a single file.
With that file it will only work on the targeted IP given using msfconsole 

#pymetasploit
In this is code that is used to automate msfconsole portion of the code above.
This is not my code, I got this from the website listed below and followed the tutorial

https://infosecaddicts.com/python-and-metasploit/#:~:text=Python%3A%20is%20an%20object%2Doriented,very%20useful%20for%20process%20automation
