# Sublime Text 3 - User Directory

### Pre-installation

Follow this guide on how to get Sublime Text 3 up and running on your system:

[http://rosslawley.co.uk/posts/switching-to-sublimetext-3/](http://rosslawley.co.uk/posts/switching-to-sublimetext-3/)

Once you have ST3 running, you're ready to proceed...

### Installation

- Open a Terminal and run these commands:

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
rm -rf User
git clone git@github.com:edjames/sublime-text-3-user-settings.git User
```

- Restart ST3.
- Ensure you have Package Control installed; if not, install it and restart ST3 once more.

### Cheatsheet

[http://www.cheatography.com/grokling/cheat-sheets/sublime-text-3-for-rails/](http://www.cheatography.com/grokling/cheat-sheets/sublime-text-3-for-rails/)

### Installed packages

**Pro tip:** Instead of installing each package separately, use the "Package Control: Advanced Install Packages" command, and use this comma-separated list do do it all in one go:

```
AdvancedNewFile, Alignment, ApplySyntax, BeautifyRuby, Copy Relative Path, HTML-CSS-JS Prettify, jQuery, Origami, PackageResourceViewer, RSpec, Ruby Block Converter, Ruby Hash Converter, Ruby Slim, SideBarEnhancements, sublime-github, SublimeGit, SublimeLinter, SublimeLinter-eslint, SublimeLinter-rubocop, ToggleQuotes
```

These are the installed packages:

- AdvancedNewFile
- Alignment
- ApplySyntax
- BeautifyRuby
- Copy Relative Path
- HTML-CSS-JS Prettify
- jQuery
- Origami
- PackageResourceViewer
- RSpec
- Ruby Block Converter
- Ruby Hash Converter
- Ruby Slim
- SideBarEnhancements
- sublime-github
- SublimeGit
- SublimeLinter
- SublimeLinter-eslint
- SublimeLinter-rubocop
- ToggleQuotes

### Contributing

If you want to contribute:

- Check out the latest master to make sure the feature hasn’t been implemented or the bug hasn’t been fixed yet
- Check out the issue tracker to make sure someone already hasn’t requested it and/or contributed it
- Fork the project
- Start a feature/bugfix branch
- Commit and push until you are happy with your contribution
- Send me a pull request

### Credits

- Snippets from [https://github.com/tennantje/railsdev-sublime-snippets](https://github.com/tennantje/railsdev-sublime-snippets)

### Copyright

Copyright (c) 2024 Ed James. See LICENSE for details.
