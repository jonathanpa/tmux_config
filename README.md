# My custom Tmux config

You can find my custom Tmux config in the `tmux.conf` file.

## OS and branches

For OSX, please use the `master` branch.
For Ubuntu and other Linux systems, please use the `ubuntu` branch.

## Customizations

The main customizations are the following :

* Remap the prefix key to **Ctrl+g**.
* Use vim movements keys to select panes : *Ctrl+g* + (**h**/**j**/**k**/**l**).
* If you are not easy with the vim movements keys, you can move through the differents panes by using **Alt** with the **arrows** keys.
* The terminal type is set to **screen-256color** to use theme as molokai, solorized, etc.
* The Tmux config can be reloaded in a running Tmux session with *Ctrl+g* + **r**.
* The mouse scrolling can be enabled with *Ctrl+g* + **m** and disabled with *Ctrl+g* + **o**.
* Horizontal split and vertical split are done respectively with *Ctrl+g* + **_** and *Ctrl+g* + **|**.
* Panes can be resized with *Ctrl+g* + the **arrows** keys.
* Move the previous (left) tab with **Ctrl** + **q** and move the next (right) window with **Ctrl** + **s**.
* Enter to the Tmux *select* mode with *Ctrl+g* + **Esc**. Then you can **v** to select text, **y** to copy and **p** to paste in *select* mode (similar keys you could use in vim).
* *Ctrl+g* + **p** to paste in Tmux *normal* mode.
* Clear the scroll buffer history of current pane with *Ctrl+g* + **k**.
* Copy the *existing* contents of the Tmux clipboard to the OSX clipboard with **Ctrl** + **y**.
* Maximize a pane with *Ctrl+g* + **+** and minimize it with *Ctrl+g* + **-**.
