My config dwm

Step 1:
Clone repository dwm

  $ git clone http://git.suckless.org/dwm

Step 2:
Compile dwm

  $ make -C ~/dwm

Step 3: 
create symbolic link config.h to .dwmrc

  $ ln -s ~/dwm/config.h .dmrc 
  
Step 5:
Give permission to run scripts "dwm-start", "dwm-status"

  $ sudo chmod a+x dwm-start 
  $ sudo chmod a+x dwm-status
  
Step 6:
Copy scripts dwm-start in PATH /usr/bin

  $ sudo cp dwm-start /usr/bin
  $ sudo cp dwm-status /usr/bin

Step 7:
Reboot system 
Selected login manager lightdm the option "dwm-start"




