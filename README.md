# switch-emacs-config
Utility for easy symlinking alternative versions of .emacs.d

# Some starter kits
http://ergoemacs.org/misc/list_of_emacs_starter_kits.html

# Usage

* copy file the switch-emacs-config-rb to somewhere in yout $PATH
* make it executable
* run it

# Example run

    $ switch-emacs-config.rb

```
this action will overwrite the existing symlink
pointing to /home/your-username/.emacs.d-emacs-starter-kit

Select emacs config
0 .emacs.d-emacs-starter-kit
1 .emacs.d-prelude
2 .emacs.d-purcell
Option> 1
```

This selects option 1 and adjusts the symlink.
