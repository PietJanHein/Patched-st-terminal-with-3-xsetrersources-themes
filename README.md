This is siduck his patched st terminal, which was forked from Luke Smith his patches, as I understand it. The only differences are the set font (much better for high DPI displays) and 2 hotkeys. I also added 3 xresource-themes: dracula, onedark and Catpppuccin. 
To use the terminal: 
Download the tar, then `tar -xzvf`, cd into the directory and `sudo make install`. 
To change the theming: `xrdb merge <path_xresources_file>`, then open a new instance of the st-terminal and the theming will be applied. To keep using the same theming you will have to run this command automatically before your graphical environment or shell starts. 
