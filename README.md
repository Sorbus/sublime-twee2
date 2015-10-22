Sublime Twee2
============

*twee2* Harlowe source code syntax highlighting for Sublime Text 2 and 3, based on [monospaced's sublime-twee](https://github.com/monospaced/sublime-twee).

*twee2* is a command-line tool for writing hypertext stories.

*Harlowe* is its default template. sublime-twee is designed for the older Sugarcube format; while twee2 (and Twine 2) support it, many people prefer newer formats.

* [twee2 documentationn](https://avapoet.github.io/twee2/documentation.html)

* [twee2 source](https://github.com/avapoet/twee2)

## Install

### Package Control

The easiest way to install this is with [Package Control](http://wbond.net/sublime_packages/package_control).

* If you just went and installed Package Control, you probably need to restart Sublime Text 2 before doing this next bit.
* Bring up the Command Palette (Command+Shift+p on OS X, Control+Shift+p on Linux/Windows).
* Select "Package Control: Add Repository"
* Enter "https://github.com/Sorbus/sublime-twee"
* Bring up the Command Palette again
* Select "Package Control: Install Package" (it'll take a few seconds)
* Select sublime-twee2 when the list appears (or type "twee2" and press enter)
* Package Control will automatically keep Twee up to date with the latest version.

### Git

Clone this repository into the Packages directory.

If you need to find the Packages directory, access the Console (Control+`) and enter the following command:

    print sublime.packages_path()

### Manual

Drop the Twee2.tmLanguage file into your Packages folder (Preferences > Browse Packages…).
