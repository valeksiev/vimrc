# vimrc 

### Based on Bozhidar Dryanovsky's [vimrc](https://github.com/bdryanovski/vimrc/).

## Installation:

### Linux
```
git clone http://bdryanovski@github.com/bdryanovski/vimrc.git $HOME/.vim
cd $HOME/.vim
git submodule update --init
ln $HOME/.vim/vimrc.vim $HOME/.vimrc
```

### Windows
```
git clone http://bdryanovski@github.com/bdryanovski/vimrc.git C:/Users/xxx/vimfiles/
cd C:/Users/xxx/vimfiles/
git submodule update --init
copy C:/Users/xxx/vimfiles/vimrc.vim C:/Users/xxx/_vimrc
```

## Files 
### Settings and Mapping
    * `vimsrc/_settings.vim` - All VIM settings.  
    * `vimsrc/_mapping.vim` - Custom keys and shortcuts.  
    * `vimsrc/_plugins.vim` - Keep plugin settings.  

### OS 
    * `vimsrc/unixrc.vim` - If VIM run on \*unix system. 
    * `vimsrc/win32rc.vim` - If VIM run on Windows system.
 
