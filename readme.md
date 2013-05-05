This project adds [LiveScript] syntax highlighting to the gedit text editor. (and any other gtksourceview compliant text editor)

[LiveScript]: http://livescript.net

### Installation and Use

1. Download and place live_script.lang in `~/.local/share/gtksourceview-3.0/language-specs` or `/usr/share/gtksourceview-3.0/language-specs`

    > Note: if those directories don't exist, make them and gedit will know what to do.
    > **Important:** if you are using GTK2 (e.g. old Gnome) use `gtksourceview-2.0/language-specs` folder instead of 3.0.

2. Run gedit and open a LiveScript file.

Patches and improvements welcome!

![screenshot](https://raw.github.com/train255/gedit-livescript/master/screenshot/screenshot1.png)
![screenshot](https://raw.github.com/train255/gedit-livescript/master/screenshot/screenshot2.png)

