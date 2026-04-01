# How to navigate
#Levels 0-7
these are still the basic and beginning level of bandit, most of the passwords can be found with commands like; ls, cat, file, cd, grep. 
All you have to do is to apply the necessary flags required, e.g to list hidden files, you use "ls -a" command.

#Levels 7-12
this stretch of levels involved encoding, decoding and searxhing within files for clues.
relevant commands to be used include: sort, uniq, strings, base64.

#Levels 12-14
/tmp is  a directory for temporary storage and it is particularly useful when woeking with a terminal where you don't have full executable permissions, when you create a file in tmp, you have the necessary permissions. scp to copy files securely from a n external location, 

#Levels 15-29
from here, things started getting advanced with commands like: openssl, ncat, ssh_client, which are used for tls connection and to scan for open ports on a server (ncat)
- level 17 was like a breather where the diff command was used without requiring much stress.
towards the end, i was introduced to bash scripting and how it runs various scripts in the background that the user is not aware of.

#Levels 20-24
i started getting familiar with cron and crontab which is responsible for scheduling tasks in a linux system.
level 24-25 was one of particular interest because it involved brute forcing by trying 1000 different combinations, a script had to be created to parse the digits as a loop until the correct password was gotten.

#Levels 25-34
this initially started with applying some knowledge of shell and how different shell can be used to start a session/terminal.
we later progressed into retrieving items from a git repository provided, the command of interest was git command and i had to go through its man page to learn the various flag available with it and how to use them tpo retrieve the passwords
