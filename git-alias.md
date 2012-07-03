#Git Alias

Working with git? These aliases will save you hours!
 
I was just watching a friend of mine work with git, and he'd always type all the git commands in full, like git status and git push. I realized that he must not be the only one to do so, so I decided to write this quick blog post and encourage everyone to create Huffman coded aliases for the most commonly used commands. Instead of typing git status, alias it to gs. Instead of git add, alias it to ga, etc.

Here are a bunch of aliases that I created for 99% of git commands I ever use:

    alias ga='git add'
    alias gp='git push'
    alias gl='git log'
    alias gs='git status'
    alias gd='git diff'
    alias gdc='git diff --cached'
    alias gm='git commit -m'
    alias gma='git commit -am'
    alias gb='git branch'
    alias gc='git checkout'
    alias gra='git remote add'
    alias grr='git remote rm'
    alias gpu='git pull'
    alias gcl='git clone'

Here is my typical workflow with these command:

    $ vim file.c
    $ gd                     # git diff
    $ ga file.c              # git add file.c
    $ gm "added feature x"   # git commit -m "added feature x"
    $ ...
    $ gp                     # git push

Short and sweet!