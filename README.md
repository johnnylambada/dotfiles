# dotfiles
John's dotfiles

# Don't store secrets here!  Store them in ~/.env and source that file before scripts/init

## How to use this project

The best way is to make a separate private repo that is a branch off of this repo. See
[this article](https://24ways.org/2013/keeping-parts-of-your-codebase-private-on-github)
for instructions on how to set this up.

## ~/.bash_profile

```
. ~/.env                                    # secrets
. ~/dotfiles/scripts/init                   # set up environment
[ -r ~/.bashrc ] && source ~/.bashrc        # exec .bashrc too!
######################################################
### if anything is added to the end of this file,
### move the lines to somewhere in ~/dotfiles
######################################################
```
