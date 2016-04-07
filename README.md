rails-lazy-sublime-snippets
====================

A collection of [Sublime Text](http://www.sublimetext.com/) snippets useful for writing rails.

##Installation

Checkout the source code into Sublime Text's packages directory. The location is system specific:

### For OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ git clone git://github.com/wayne5540/rails-lazy-sublime-snippets.git Rails_Lazy_Snippets

### For Windows

    $ cd %APPDATA%/Sublime Text 2/Packages/
    $ git clone git://github.com/wayne5540/rails-lazy-sublime-snippets.git Rails_Lazy_Snippets

### For Linux

    $ cd ~/.Sublime Text 2/Packages/
    $ git clone git://github.com/wayne5540/rails-lazy-sublime-snippets.git Rails_Lazy_Snippets

##Snippets and Bindings





##Resolve conflicting tab trigger

It is possible for the snippets in this package to conflict with other Sublime text plugins, such as the built-in Rails package or [Rails Developer Snippets](https://github.com/j10io/railsdev-sublime-snippets). You may want to disable unwanted snippets.

### For Sublime Text 2

Delete unwanted snippet files from `~/Library/Application\ Support/Sublime\ Text\ 2/Packages/<PackageName>/`

### For Sublime Text 3

1. Install the [PackageResourceViewer](https://github.com/skuroda/PackageResourceViewer) Package
2. Open unwanted snippets with `PackageResourceViewer: Open Resource` command and comment it out

##Questions, Comments, Concerns?

Feel free to submit a pull request with any snippets you would like to add to the project. If you have any problems or suggestions you can file an issue.

##License

Released under [WTFPL, Version 2](https://raw.github.com/wayne5540/rails-lazy-sublime-snippets/master/LICENSE.txt)
