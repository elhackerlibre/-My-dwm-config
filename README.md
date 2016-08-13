My config dwm

Step 1:
Clone repository dwm

  $ git clone http://git.suckless.org/dwm

Step 2:
Compile dwm

  $ cd dwm
  
  $ make -C ~/dwm

Step 3: 
create symbolic link config.h to .dwmrc

  $ cd ..
  
  $ ln -s ~/dwm/config.h .dmrc 
  
Step 5:
Give permission to run scripts "dwm-personalized"

  $ sudo chmod a+x dwm-personalized 
  
Step 6:
Copy scripts dwm-start in PATH /usr/bin

  $ sudo cp dwm-personalized /usr/bin

Step 7:
Reboot system 
Selected login manager lightdm the option "dwm-personalized"




