# Bandit Level 3

## Goal
- Find the password for the next level in a file called --spaces in this filename--

## Commands I used
- ssh 
- ls
- cat

## What I learned
- This file has two catches: spaces in the name and dashes at the start.
- Spaces are a problem because the terminal treats each space as a separator between different items. So it would read --spaces, in, this, and filename-- as four separate things instead of one filename.
- wrap the whole name in quotes so the terminal sees it as one item, and put ./ in front
