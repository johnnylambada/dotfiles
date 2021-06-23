# dotfiles
John's dotfiles

# Don't store secrets here!  Store them in ~/.env and source that file before scripts/init

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
