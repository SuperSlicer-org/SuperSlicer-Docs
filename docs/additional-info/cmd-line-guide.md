# Command Line Guide

We strongly recommend use command `--help` to see current interface.

**Note:** Windows users have to use `prusa-slicer-console.exe`

The command line interface is the [same as in upstream Slic3r](https://manual.slic3r.org/advanced/command-line), with the following modifications:

- instead of `--help-options` we have `--help-fff` and `--help-sla`
- we have an additional parameter `--loglevel` to configure severity of messages printed out to the console
- we support `--export-sla`, not `--export-sla-svg` nor `--export-svg`
- we don't support `--cut-grid` , `--cut-x` , `--cut-y` , `--autosave`

As may be expected, PrusaSlicer loads the profiles from an AMF or 3MF file when slicing from the command line, and the individual slicing parameters specified on command line overwrite those imported from the AMF or 3MF file.


## Specify a custom config directory

This can be done with a command line arguement when launching SuperSlicer from a terminal or command line.

Windows: `C:\Program Files\SuperSlicer\superslicer.exe --datadir \path\to\configdir`

Mac: `open -n /Applications/SuperSlicer.app --args --datadir /path/to/configdir`

Linux: `/usr/bin/SuperSlicer/superslicer --datadir /path/to/configdir`
