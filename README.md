# Css-for-Ubuntu-Titlebar-Shrink_total-slim-titlebar instructions for ultra slim terminal titlebar and square window:

1. Download Ubuntu total slim titlebar.css file and rename:
     > gtk.css
3. Paste the file in Ubuntu directory:
     > /home/tahmid/.config/gtk-3.0
4. Install from Ubuntu Software
     > Synaptic Package Manager  
5. Search for: 
     > dconf-editor
6. Right click and select "Mark for installation" from the search result
7. open dconf-editor and click "I'll be careful" and search for:
    > Terminal
8. Now follow by double clicking and make it false:
    > legacy/headerbar 
9. Now Turn off but when you need to customize your default terminal just turn on again and turn off when done:
    > default-show-menubar
10. Done !
    
