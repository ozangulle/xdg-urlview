# xdg-urlview

Extract URLs from a text file and allow the user to select via a menu

This is a fork of the original [urlview](https://github.com/sigpipe/urlview) which seems to be abandoned.

The binary is called "urlview" in order to have full compatibility with the original.

## Extra feature

xdg-urlview conforms with the Freedesktop XDG Base Directory Specification concerning the config file.

The list of configuration locations in order of precedence:
- $XDG_CONFIG_HOME/urlview/urlview
- $HOME/.config/urlview/urlview
- $HOME/.urlview.
