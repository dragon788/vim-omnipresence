# vim-omnipresence

**NOTE**: Work in progress!

This vim plugin creates hotkey to launch vim for any common operating system editable area. You can then change the text, save the document and exit. The text in the editable area should be replaced with your changes done in vim editor.

## Status

* Windows support: Full
    * This will launch AutoHotkey script which will be visible in the system tray (with vim icon). Script will install itself in the Startup folder of the current user. Hotkey can be configured via `vimrc`. 
    * Set mapping: `let g:omnipresence_hotkey = 'F11'` (note: key mapping is currently [AHK style](http://www.autohotkey.com/docs/misc/Remap.htm))
* Linux support: Partial 
    * No automatic hotkey creation
    * No automatic dependency installation
* Mac support: ?

## Related work

* [cknadler / vim-anywhere](https://github.com/cknadler/vim-anywhere)
* Windows only: [Edit everywhere with vim](http://www.autohotkey.com/board/topic/78526-edit-everywhere-with-vim/)
