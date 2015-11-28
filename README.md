# .dotsync
A simple bash script for syncing your dot files (Very rudimentary)


Bootstrapping:
The first thing you will want to do with this is chose a location that is webaccessable. And set the remote path in .dotsync
After you have set that up you will want to copy it to that remote directory and to your home directory. 
When you run it, it will update itself and any other files you specify in it. 

If you want it to auto run every time you log in, make sure you copy the .bashrc file to your remote path. .dotsync will append it to the current .bashrc file.
