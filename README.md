# Sublime Text 3 - User Directory

### Pre-installation

Follow this guide on how to get Sublime Text 3 up and running on your system:

[http://rosslawley.co.uk/posts/switching-to-sublimetext-3/](http://rosslawley.co.uk/posts/switching-to-sublimetext-3/)

Once you have ST3 running, you're ready to proceed...

### Installation

Open a Terminal and run these commands:

    cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
    rm -rf User
    git clone git@github.com:edjames/sublime-text-3-user-settings.git User

Restart ST3.

### Cheatsheet

[http://www.cheatography.com/grokling/cheat-sheets/sublime-text-3-for-rails/](http://www.cheatography.com/grokling/cheat-sheets/sublime-text-3-for-rails/)

### Post-installation

Some plugins are not yet available through Package Control (yet) so they have ot be manually installed, as follows:

All packages need to be installed in the same location:

    cd "~/Library/Application Support/Sublime Text 3/Packages/"

###### SublimeRailsNav

[https://github.com/noklesta/SublimeRailsNav](https://github.com/noklesta/SublimeRailsNav)

    git clone git://github.com/noklesta/SublimeRailsNav
    cd SublimeRailsNav
    git checkout ST3

###### SublimeToggleSymbol

[https://github.com/zoomix/SublimeToggleSymbol](https://github.com/zoomix/SublimeToggleSymbol)

    git clone git://github.com/zoomix/SublimeToggleSymbol

Restart ST3.

### Installed packages

Package Control settings are not in source control.
These are the installed packages:

- AdvancedNewFile
- Alignment
- ApplySyntax
- BeautifyRuby
- Dash
- GitGutter
- jQuery
- JsFormat
- RSpec
- Ruby Block Converter
- Ruby Hash Converter
- SideBarEnhancements
- sublime-gem-browser
- SublimeGit
- Theme - Soda
- Theme - Sodarized
- ToggleQuotes

### Contributing

If you want to contribute:

- Check out the latest master to make sure the feature hasn’t been implemented or the bug hasn’t been fixed yet
- Check out the issue tracker to make sure someone already hasn’t requested it and/or contributed it
- Fork the project
- Start a feature/bugfix branch
- Commit and push until you are happy with your contribution
- Send me a pull request

### Copyright

Copyright (c) 2015 Ed James. See LICENSE for details.

