# packages

The stuff I need on my Mac

Generated with [brewpack](https://github.com/rouanw/brewpack).

## Manual steps

- Install brew `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` (needs Xcode)
- `brew update`
- `brew doctor`
- set up ssh keys
- clone dot files, cd dot files `ruby install.rb`
- install terminal theme
- cdrgs setup `cdargs --add=:mynickname:/Users/Rouan/projects/whatever`

## OSX tweaks

- right click (two-finger tap)
- remove spotlight keyboard shortcut (and set it up in alfred)
- key repeats
- use function keys
- default location in new finder window - finder preferences, set to home
- autohide dock
- turn off swipe between pages
- keyboard shortcuts - change move focus to next window
- switch off audible terminal bell
- disable spotlight `sudo launchctl unload -w /System/Library/LaunchDaemons/com.apple.metadata.mds.plist(http://recomhub.com/blog/how-to-disable-or-enable-spotlight-in-mac-os-x-yosemite-mavericks-mountain-lion/)
