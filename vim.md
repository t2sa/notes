#####VIM Notes
----

######Help
```shell
:help               #Get help
ctrl-]              #Follow link
ctrl-t or ctrl-o    #Go back out
vert bo help split  #Vertical botright help split
```

######Multipe Windows
```shell
:e file             #edit another file
:split file         #split window and load file
ctrl-w up           #mode cursor up a window
ctrl-w ctrl-w       #cycle windows
ctrl-w_             #maxmize current window
ctrl-w=             #equal size windows
10 ctrl-w+          #increase windows size by 10 lines
:vsplit file        #vertical split
:sview file         #read only split
:hide               #close current window
:only               #keep only current window
:ls                 #list buffers
:b 2                #open buffer #2 in current window
```

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

######Buffer
```shell
:buffers            #List buffers
:b<number>          #Open buffer in pane
```

######Splits
```shell
:sp                 #Split horizontal
:vs                 #split verticall

ctrl-w ctrl-w       #cycle through splits
ctrl-w h/k/l/j      #go left/up/right/down
```

######Shell
```shell
```

######Template
```shell
```
