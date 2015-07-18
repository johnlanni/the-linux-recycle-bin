##If the options contain -v, then the script will exec '/bin/rm' directly

##add to ~/.bashrc
`
alias rm="sh ~/bin/delete"                                                                                                                   
`

crontab:
`
15 18 * * * /home/zhangty/bin/cleanTrashCan
`