#####VIM Notes
----

######Tabs
```shell
vim -p file1 file2  #Open multiple files in tabs
:tabedit file       #Edit file in tab
:tabclose           #Close current tab
:tabclose {i}       #Close i-th tab
:tabonly            #Close all but current

:tab ball           #show each buffer in a tab
:tab help           #new help in new tab
:tab drop file      #open file new tab or jump to tab with file
:tab split          #copy current window to new tab

:tabs               #list all tabs
:tabm 0             #move current tab to first
:tabm               #move current tab to last
:tabn               #next tab
:tabp               #previous tab

gt                  #next tab
gT                  #previous tab
```
