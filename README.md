# sleepmenu
Sleeptimer dialog/menu for zipit z2 in ~6K using busybox ash script with ANSI escape sequences. 

![Main Screen](doc/sleepmenu.png?raw=true)

The reason for this is because the internal flash on the zipit Z2 is only 8 megabytes large.  From this perspective, programs like stty and dialog and seem big and bloated at ~50K and ~150K.  And someday I might just need to fork this repo and create a derivative script to control the sleep function in my linux based toaster.