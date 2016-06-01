**README.md** for livim\_vundle configuration
=============================================



#Install
1. $ cd ${LIVIM\_HOME\_DIRECTORY}
2. $ ln -s vim ~/.vim; ln -s vimrc ~/.vimrc
3. $ vim; :PluginInstall

#Key Mapping
> || F1 | F2 | F3 | F4 || F5 | F6 | F7 | F8 || F9 | F10 | F11 | F12 ||

## Show windows
* **F1**: reserved
* **F2**: show NERDTree(left)
* **F3**: show symbols in the curren file(right)
* **F4**: reserved
    
## Operations
* **F5**: switch between source/head files
* **F6**: grep symbols with cusor underline(single click for recursive grep, double click for current grep)
* **F7**: search symbol in the new split window(single-click <F7> for Vectical split window, double-click <F7> for horizonial split window)
* **F8**: search symbol in the current window
  * **s**(ymbol): for symbols referred
  * **g**(lobal): global definitions of the symbol
  * **c**(alls): find all calls to the funcation name
  * **t**(ext): find all instance of the text
  * **e**(gree): egreo search for the word
  * **f**(ile): open the filename file under cursor
  * **i**(ncludes): find files that include the filename file under cursor
  * **d**(called): find functions that under-cursor function calls

## Initialzation
* **F9**:  single click for "creat tags by ctags" 
* **F10**: reserved
* **F11**: reserved
* **F12**: single click for "create sysbol connections by cscope"
    
## Other Shortcuts
###ctags
* **<C-]>** go to definitions
* **<C-t>** reverse of <C-]>
* **<C-o>** go to point of last cursoring
* **<C-i>** reverse of <C-o>
* **gb** seek for definition of local variables
* **o** open the symbol in new tab
* **p** preview the definition in taglist windows
* **u** update the taglist
* **s** choose sort type
* **x** zoom in/out
* **+/-** expand/reverse

###cscope
    
###MRU
<leader>m: open mru windows

#Others
<C-i> <C-o>: go to next/last cursor position

# Plugin Installation Instuctions
## gocode
+ go get github.com/nsf/gocode
+ Bundle 'Blackrush/vim-gocode'
+ vim +BundleInstall
