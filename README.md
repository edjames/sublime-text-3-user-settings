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

### Post-installation

Some plugins are not yet available through Package Control (yet) so they have ot be manually installed, as follows:

All packages need to be installed in the same location:

    cd "~/Library/Application Support/Sublime Text 3/Packages/"

###### BeautifyRuby

[https://github.com/CraigWilliams/BeautifyRuby](https://github.com/CraigWilliams/BeautifyRuby)

    git clone git://github.com/CraigWilliams/BeautifyRuby

###### SublimeRailsNav

[https://github.com/noklesta/SublimeRailsNav](https://github.com/noklesta/SublimeRailsNav)

    git clone git://github.com/noklesta/SublimeRailsNav
    cd SublimeRailsNav
    git checkout ST3

###### SublimeToggleSymbol

[https://github.com/zoomix/SublimeToggleSymbol](https://github.com/zoomix/SublimeToggleSymbol)

    git clone git://github.com/zoomix/SublimeToggleSymbol

Restart ST3.

#### Note

Package Control settings are not in source control.
These are the installed packages:

- AdvancedNewFile
- Alignment
- ApplySyntax
- Better CoffeeScript
- CTags
- GitGutter
- jQuery
- JsFormat
- RSpec
- Ruby Block Converter
- Ruby Hash Converter
- Sass
- SideBarEnhancements
- sublime-gem-browser
- SublimeGit
- Theme - Soda
- Theme - Sodarized
- ToggleQuotes
