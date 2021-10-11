# nibl
A really simple nibl search script for nibl which utilises the surf web browser to display the nibl search website.

P.S. I know this is a really lazy script, but it may be useful for some people, so I just developed this so you don't have to!

Installation:
If you would like to be able to run it from your terminal, just simply clone this repo and make it executable by running 'chmod +x nibl'.
Because surf does have a daemonise function, the code will not exit until the process is terminated, meaning you will have to keep the terminal window open.

If you do not want to be able to launch this script without a terminal, all you need to do is;

1) clone the script into /usr/bin and make it executable (see previous command)
2) clone icon.jpg to /opt/NIBL (optional)
3) clone NIBL.desktop to /usr/share/applications (you may need to edit this file to add an icon and category, however I didn't as I am using i3)

Oh, and dependencies;

1) bash
2) surf

ALSO: I do not take any credit as the main code is in surf itself and of course the NIBL website. Thank you to the people over at suckless[.]org and NIBL. This script was simply just developed for convenience, nothing else.
