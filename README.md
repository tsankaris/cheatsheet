# cheatsheet
un po' di cheat sheet utili

# BASH MAC TO WINDOWS CMD
## Clear the screen

Mac: clear

Windows: cls

## Display all contents of a dir
Mac: ls -al

Windows: dir
## Change dir
Both:

cd <dir>
## Rename file
Mac: mv <file> <file>

Windows: ren <file> <file>
## Copy file
Mac: cp <file> <file>

Windows: xcopy <file> <file>
## Copy dir and subdirs
Mac: cp -R <dir> <dir>

Windows: xcopy /s <dir> <dir>
## Delete file
Mac: rm <file>

Windows: del <file>
## Delete dir
Mac: rm -rf <dir>

Windows: rmdir /s/q <dir>
## Display file contents
Mac: cat <file>

Windows: type <file>
## Print current working dir
Mac: pwd

Windows: cd
## Change file timestamp
Mac: touch <file>

Windows: type nul > <file>
## Display current user
Mac: whoami

Windows: echo %USERNAME%
## Display all env vars
Mac: env

Windows: set
## Print PATH
Mac: echo $PATH

Windows: echo %PATH%
## Print each PATH entry on new line
Mac: echo $PATH | tr ':' '\n'

Windows: echo %PATH:;=&echo.%
## Show location of a command
Mac: which <command>

Windows: where <command>
## Search file for pattern, ignore case
Mac: grep -i "<pattern>" <file>

Windows: findstr /i "<pattern>" <file>
## Search for file recursively
Mac: find . -name *<file>*

Windows: dir *<file>* /b/s
## Display networking info
Mac: ifconfig

Windows: ipconfig /all
## Display aliases
Mac: alias

Windows: doskey /macros
## Create alias
Mac: alias <alias>="<command>"

Windows: doskey <alias>=<command> $*
## Copy command output to clipboard
Mac: <command> | pbcopy

Windows: <command> | clip
## Display a line of text
Both:

echo <text>
## Display command history
Mac: history

Windows: doskey /history
