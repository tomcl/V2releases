# VisUAL2

A friendly ARM assembler and simulator for educational use.

Visual2 will run on Windows, OS-X and linux and is distributed as binaries. The total disk space requried is approximately 200MB.

## Getting Started

1. Download the [latest Visual2 binary release](https://github.com/tomcl/V2releases/releases) for your platform

### Windows

* Unzip the download anywhere on your system: the extracted files will use approximatly 200MB.
* You can then delete the downloaded zip file.
* To run the program double-click the executable `VisUAL2.exe` which can be found in the top-level unzipped directory.
* No installation is required

### OS-X

* Open the downloaded DMG file
* Drag the Visual2-darwin-x64 directory into the applications directory as normal to install
* The following warning might appear when you first try to launch the application: "Visual2" can't be opened because it is from an unidentified developer. In that case:
    * Open `System Preferences`
    * Go to `Security & Privacy`
    * In the bottom rigth corner, under `General`, click 'Open anyway'
    * Click 'Open' in the pop up window
    * If Visual2 does not seem to start, simply quit the application and re-launch


### Linux

* Untested (using standard electron-packager output)
* Unzip the download
* Run Visual2
* In case of problems check the documentation on running electron applications on your distro. Contact [me](t.clarke@ic.ac.uk) if you'd like access to the source repo [Visual2](https://github.com/ImperialCollegeLondon/Visual2) and compile Visual2 from source, which may be easier to run under linux.


## Command Line Switches

```
visual2.exe [-d|--debug] [-h|--help]
```

* Ctrl-Shift-I (in debug mode) open dev tools to show test results etc

## Visual2 Documentation

See the [documentation site](https://tomcl.github.io/visual2.github.io/).

## Notes

This is an open access repo holding releases of [Visual2](https://github.com/ImperialCollegeLondon/Visual2). 

Anyone wanting to see the closed code and/or contribute contact me and I can add.

Binaries will be posted here. Please give bug reports and user feedback on binaries as issues on this repository.
