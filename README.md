atom-custom
===========

simple customizations to make atom awesome

#### Config

config files are kept in ~/.atom

enable REACT Editor to use the more experimental and somewhat faster editor

#### install all 'starred' packages

This will install all packages you starred in your account on https://atom.io

Really handy if you switch machines a lot.

    apm stars --install

#### linters

    -g = install globally
    ..
    npm install -g coffeelint 
    npm install -g csslint
    gem install scss-lint
    gem install rubocop
    ..custom jslint found in ~/.dotfiles/bin from johnantoni

### Keyboard mapping

    CMD+OPT+<   = goto left tab
    CMD+OPT+>   = goto right tab
    CMD+SHFT+P  = open command palette
    ..
    CMD+T       = fuzzy file find
    CMD+B       = search only open files
    ..
    CMD+SHFT+B  = search only untracked files
    ..
    CMD+S       = markdown live preview
    ..
    CMD+R       = search symbols
    CMD+SHFT+R  = search tags

#### Close Find/Replace panel

    CMD+F       = open find/replace panel
    ESC         = close find/replace panel

#### Read more

* git integration .. http://blog.atom.io/2014/03/13/git-integration.html
* git-grep .. https://github.com/mizchi/atom-git-grep

#### Open in Atom - Alfred 2 workflow

* [https://github.com/franzheidl/alfred-workflows/tree/master/open-with-atom](https://github.com/franzheidl/alfred-workflows/tree/master/open-with-atom)

### Copyright

Copyright (c) 2014 John Griffiths. See [LICENSE](LICENSE) for details.
