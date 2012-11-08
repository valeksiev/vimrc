# vimrc 

### Based on Bozhidar Dryanovsky's [vimrc](https://github.com/bdryanovski/vimrc/).

## Installation:

### Linux
```
git clone https://github.com/valeksiev/vimrc.git path/to/vimconfs
cd path/to/vimconfs
git submodule update --init
ln -s path/to/vimconfs/vimrc.vim $HOME/.vimrc
ln -s path/to/vimconfs $HOME/.vim
```

## Files 
### Settings and Mapping
    * `vimsrc/_settings.vim` - All VIM settings.  
    * `vimsrc/_mapping.vim` - Custom keys and shortcuts.  
    * `vimsrc/_plugins.vim` - Keep plugin settings.  

### OS 
    * `vimsrc/unixrc.vim` - If VIM run on \*unix system. 
    * `vimsrc/win32rc.vim` - If VIM run on Windows system.
 
