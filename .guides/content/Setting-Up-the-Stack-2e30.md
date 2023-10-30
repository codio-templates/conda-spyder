---

Spyder opens automatically when the box starts, and **this stack already has everything you need** if you want to use it for your own projects. If you want to create your own or if you need to make changes to the way it works, this is how we created it:

1. From the `Tools` menu, go to `Install Software` and then install `X Server`, which allows Codio to run GUI applications.
1. You need the `Autostart Support`, also available in `Install Software` to run a `bash` file when the box starts.
1. To install Spyder, you need Anaconda, which was also installed in this stack. 
1. Then inside this stack we created the file `startup.sh` in `/home/codio/` to open Spyder when the box starts. 

