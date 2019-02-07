# dmenu
dmenu is a dynamic menu for X, originally designed for dwm. It manages large numbers of user-defined menu items efficiently. (by suckless) [customized] 
Original: https://tools.suckless.org/dmenu/

## Patches/Customizations in use
- none
  - nourl

## Keyboard Customizations
none

## Patching process
My patching strategy:
* upstream branch is pulled and in sync with suckless upstream
* dev is the testing version
* master is my normal current running version (live)

To apply a new patch:
* checkout upstream
* branch upstream to newpatch
* apply patch to newpatch name
* commit and push, resolving any conflicts
* checkout dev
* merge newpatch, resolving any conflicts
* push newpatch
* test dev branch for functionality
* merge dev into master
* test master
