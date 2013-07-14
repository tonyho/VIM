Vim/Gvim
===

 I found this vim package in[ Here](http://www.oschina.net/code/snippet_574132_13357 "OSChina") and I modify some of the configurations and Add two registry file to add two entry (`open in gvim tab` and `Open with gvim`) in Windows right click context menu.

----------

# For Windows: #
1. After clone the this repo, move this repo directory to where you want to place. 
2. Add the path to system environment variable[path], if you want to using the ctags and cscope.
3. Modify the path string where store the gvim.exe in registry file `EditWithVim-tab.reg`  and  `EditWithVim.reg`. The default is `D:\\software\\gVimPortable\\vim73\\gvim.exe\`
4. Double click the registry files to merge them to system. As the registry file name imply, each of them will add a enty in right click context menu.

# For Linux #

1. Clone this repo.
2. Install the vim(or gvim) using the proper commands, for example in Ubuntu: `sudo apt-get install vim`
3. Install the cscope, ctags and taglist plugin.
4. Move the _vimrc file to you home directory, and rename it to .vimrc
5. Move the vimfiles directory to you home directory, and rename it to .vim
# For Cygwin #
These is no much different between cygwin and linux to use vim.  

----------

----------

