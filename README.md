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

	cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
	git clone git://github.com/SublimeText/RSpec.git
	git clone https://github.com/NaN1488/sublime-gem-browser.git
	git clone http://github.com/noklesta/SublimeRailsNav
	cd SublimeRailsNav
	git checkout ST3

Restart ST3.

#### Note

Package Control settings are not in source control.
These are the installed packages:

- AdvancedNewFile
- Alignment
- ApplySyntax
- BeautifyRuby
- Better CoffeeScript
- CTags
- EmberScript
- GitGutter
- jQuery
- JsFormat
- RSpec
- Sass
- SideBarEnhancements
- sublime-gem-browser
- SublimeGit
- SublimeRailsNav
- Theme - Soda
- Theme - Sodarized
