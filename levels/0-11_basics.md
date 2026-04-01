# Levels 0-11: SSH Basics & File Navigation
These early levels helped me get comfortable with the Linux terminal and remote access.

### Key Levels & Takeaways

**Level 0-1: SSH Connection & Reading Files**
- Learned how to SSH into a remote server using `ssh bandit0@bandit.labs.overthewire.org -p 2220`
- Used `cat readme` to read the password for the next level
- **Real-world use**: Basic remote server access needed in IT Support and SOC roles

**Level 2: Handling Special Filenames**
- File started with `-` so normal `cat` didn't work
- Solution: `cat < -` or `cat ./-
- **Learned**: How to handle tricky filenames safely

**Level 3-5: Hidden Files & Spaces in Names**
- Used `ls -a` to show hidden files
- Handled filenames with spaces using quotes or tab completion
- **Learned**: Importance of `ls -a` and proper quoting

**Level 6-11: Finding Files**
- Used `find`, `ls -l`, and `file` command to locate files by size, owner, or type
- Practiced searching the entire filesystem
- **Real-world use**: Quickly locating config files or suspicious files during troubleshooting

**Overall from 0-11**:
Built strong foundation in terminal navigation, file reading, and basic Linux commands. These skills make daily CLI work much faster.

