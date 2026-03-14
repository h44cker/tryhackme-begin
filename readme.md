
Some tools:
LinPeas: https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite/tree/master/linPEAS

LinEnum: https://github.com/rebootuser/LinEnum

LES (Linux Exploit Suggester): https://github.com/mzet-/linux-exploit-suggester

Linux Smart Enumeration: https://github.com/diego-treitos/linux-smart-enumeration

Linux Priv Checker: https://github.com/linted/linuxprivchecker




For kernel version vulnerabilitiy:

Research sources:

Based on your findings, you can use Google to search for an existing exploit code.
Sources such as https://www.cvedetails.com/ can also be useful.
Another alternative would be to use a script like LES (Linux Exploit Suggester) but remember that these tools can generate false positives (report a kernel vulnerability that does not affect the target system) or false negatives (not report any kernel vulnerabilities although the kernel is vulnerable).
Sources such as
https://www.cvedetails.com/

Hints/Notes:

Being too specific about the kernel version when searching for exploits on Google, Exploit-db, or searchsploit
Be sure you understand how the exploit code works BEFORE you launch it. Some exploit codes can make changes on the operating system that would make them unsecured in further use or make irreversible changes to the system, creating problems later. Of course, these may not be great concerns within a lab or CTF environment, but these are absolute no-nos during a real penetration testing engagement.
Some exploits may require further interaction once they are run. Read all comments and instructions provided with the exploit code.
You can transfer the exploit code from your machine to the target system using the SimpleHTTPServer Python module and wget respectively.
