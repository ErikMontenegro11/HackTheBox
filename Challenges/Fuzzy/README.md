## Fuzzy
Objective: We have gained access to some infrastructure which we believe is connected to the internal network of our target. We need you to help obtain the administrator password for the website they are currently developing. 

## Tools
gobuster : Gobuster is a tool used to brute-force URIs (directories and files) in web sites.

## Walkthrough

 - Used 'gobuster' in Kali to try and enumerate names of hidden directories within the website.
 Useage: 'gobuster dir -u http://docker.hackthebox.eu:30829/ -w /usr/share/wordlists/common.txt' 
 dir (Directory mode)
 -u url
 -w path to desired word list for brute forcing
 
 ![](gbhome.png)
 
 - In the output, we can see that gobuster discovered an interesting directory titled "api."  In computing, we know an API (Applicaton Programming Interface) lists many operations that developers can use, along with a description of what they do.  It is a set of definitions and protocols for building and integrating application software.  The homepage of the website also announces that that developers are currently working on login functionality and a password reset tool.  
 
 
 
 
 
 
 
 

