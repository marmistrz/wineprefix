# wineprefix
A lightweight script to ease up wineprefix management.

## Where is the new prefix created?

When invoked as `wineprefix foo`, the new wineprefix is created in
`$HOME/.wineprefix/foo`

## Examples

```
wineprefix other winetricks  # if we want to install a library
wineprefix other wine explorer  # or if we want to launch the explorer
```
