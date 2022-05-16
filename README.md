# Css-for-Ubuntu-Titlebar-Shrink_total-slim-titlebar instructions for ultra slim terminal titlebar and square window:

1. Download Ubuntu total slim titlebar.css file and rename it gtk.css
2. Paste the file in Ubuntu directory:
     > /home/tahmid/.config/gtk-3.0
3. Install from Ubuntu Software
     > Synaptic Package Manager  
4. Search for: 
     > dconf-editor
5. Right click and select Mark for installation from the search result
6. open dconf-editor and click "I'll be careful" and search for:
    > Terminal
7. Now follow by double clicking:
    > legacy/headerbar and make it false
8. Now Turn off:
    > default-show-menubar
   when you need to customize your default terminal just turn on again and turn off when done:
   > default-show-menubar
9. Done !
    
