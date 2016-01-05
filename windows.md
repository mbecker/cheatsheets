# Windows Cheatsheet

## To create a subst folder
1. Start a commandprompt (no admin privileges needed)
2. Use cd to navigate to the folder you want to go (you can use tab to autocomplete names
3. type subst j: . to create the driveletter association. (instead of the . you can also type the entire path)
4. Now in explorer you have a new letter. Go to it and do whatever you need to do to the .cache files.
5. Go back to your cmd window and type subst /d j: to remove the drive or alternatively, restart your pc.
Tip: If you are in explorer at the right path, just type in subst j: . in the addressbar and press enter. A command window will pop up, execute the command and close again, and there you go, a new drive pops up in explorer.
