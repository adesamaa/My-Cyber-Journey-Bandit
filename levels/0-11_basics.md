# Levels 0-11: SSH Basics & File Navigation
These levels help to build core terminal comfort.
•  Level 0: Connect via SSH to the Bandit server (username **bandit0**, password **bandit0**).
    •  Key takeaway: SSH syntax and remote login basics.
    •  Real-world use: Remote server access in IT Support or SOC troubleshooting.
    
•  Level 1–2: Reading files (`cat` readme), handling tricky filenames (file starting with -).
    •  Key takeaway: `ls`, `cat`, and dealing with special characters in filenames.
    •  Real-world use: Finding and reading config/logs when filenames are unusual.
    I got stuck for about 10 minutes figuring out how to navigate the filename with '-' but learned to use "cat < -" for it
    
•  Level 3–5: Hidden files (`ls -a`), spaces in filenames, finding the human-readable file among many.
    •  Key takeaway: `ls -a` for hidden files, quoting filenames with spaces.
    •  Real-world use: Locating hidden config files or logs during investigations.
    
•  Level 6–11: Finding files by size, owner, permissions, or location; basic string searching.
    •  Key takeaway: `find`, `ls -l`, `file` command, and simple filtering.
    •  Real-world use: Locating suspicious files or logs on a system quickly.
    #`ls -l` gives full list of the items in the present directory with their permissions, owners and group owners.

