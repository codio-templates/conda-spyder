---

The layout for this page is set up to auto-open Spyder. Click **Edit** and then the **Layout** button to see the set up.

Spyder opens automatically once the box starts, and this stack already have everything you need if you want to use it for your own projects. If you want to create your own or if you need to make changes to the way it works, this is how we enabled it:

1. From the `Tools` menu, go to `Install Software` and then install `X Server`, which allows Codio to run GUI applications.
1. You also need the `Autostart Support`, also available in `Install Software` to run a `bash` file when the box starts.
1. Then inside this stack we created the file `startup.sh` in `/home/codio/`. 
1. To install Spyder, you also need Anaconda, which was also installed in this stack. 

Continue with the next pages if you need help setting up these tools on your own stack or if you need to make changes.