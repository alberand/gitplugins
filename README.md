This repository contains my `~/.vim` directory

Add new plugin:

    $ vim ~/.vimrc
    # Add `Plugin 'user/reponame'`
    # In vim run :PluginInstall
    $ cd ~/.vim
    $ git submodule add https://github.com/user/plugin bundle/plugin
    $ git commit -m "Add plugin"
    $ git push

Installation:

    git clone git://github.com/alberand/vimplugins.git ~/.vim

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update
