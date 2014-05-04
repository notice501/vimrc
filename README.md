vimrc
=====
#FooCoder's vimrc
-------------
#Installation

###make links 

	git clone git@github.com:notice501/vimrc.git
	ln -s vimrc ~/.vim
    ln -s ~/.vim/vimrc ~/.vimrc
    
###use vundle to manage plugins

I use [vundle](https://github.com/gmarik/Vundle.vim) to manage my plugins. Just run
`:BundleInstall`to install all the plugins.


  
#Requirements
	
Because I use neocomplete, which requires Vim 7.3.885+ compiled with if_lua. And many plugins requires python and ruby. So, make sure your vim version is 7.3.885+ and compiled with if_lua, python and ruby.

OS X:

	brew install macvim --with-cscope --with-lua --enable-pythoninterp --enable-rubyinterp --HEAD --override-system-vim  

#Included Plugins

You can visit my blog - [foocoder.com](http://foocoder.com),where I posted detailed description of each plugin.

some plugins:

* [ctrlp.vim](https://github.com/kien/ctrlp.vim): Fuzzy file, buffer, mru and tag finder.
* [YankRing](https://github.com/vim-scripts/YankRing.vim): Maintains a history of previous yanks, changes and deletes
* To Be Continued...

#To Be Continued...