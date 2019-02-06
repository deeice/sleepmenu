# sleepmenu
Sleeptimer dialog/menu for zipit z2 in about 6K using busybox ash script with ANSI escape sequences. 

![Main Screen](doc/sleepmenu.png?raw=true)

The reason for this is because the internal flash on the zipit Z2 is only 8 megabytes large.  And from that perspective, even relatively small programs like stty and dialog and seem big and bloated at around 50 to 150K.  And who knows, someday I just might need to fork this repo and create a derivative script to control the sleep function in my linux based toaster.