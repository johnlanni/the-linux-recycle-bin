##note

If the options contain -v, then the script will exec '/bin/rm' directly

##use

`
mv cleanTrashCan  delete  logTrashDir  restoreTrash  ~/bin
chmod +x cleanTrashCan  delete  logTrashDir  restoreTrash

`

##add to ~/.bashrc

`
alias rm="sh ~/bin/delete"                                                                                                                   
`

##restore

`
cd ~/trash
restoreTrash filename_xxx
`

##crontab

`
15 18 * * * /home/zhangty/bin/cleanTrashCan
`
