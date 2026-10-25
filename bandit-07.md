# Bandit Level 7

## Goal
- Find the password for the next level stored somewhere on the server and has the properties below:
- owned by user bandit7
- owned by group bandit6
- 33 bytes in size

## Commands I used
- ssh 
- find
- cat 

## What I learned
- Used the find command and started the search from very top of the file system /
- Specified using command options or parameters
- included 2>/dev/null to hide the “Permission denied” errors, which would otherwise flood my screen. It sends error messages into a black hole instead of printing them.
