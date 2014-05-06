##aas

This means that git thinks that it can correctly set the executable bit on checked out files, but when it attempts to do so it doesn't work (or at least not in a way that it can read). When it then reads back the status of those files it looks like the executable bit has been deliberately unset. Setting core.filemode to false tells git to ignore any executable bit changes on the filesystem so it won't view this as a change. If you do need to stage an executable bit change it does mean that you have to manually do 

`http:/www.baodu.com/asasas/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z/P1G6VFgR/d-g-z`aasas
a
