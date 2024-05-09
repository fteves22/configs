All environment configs for easy setup on a new machine.

## Vim

1. Create a new `.vimrc` file in your HOME directory.

`touch ~/.vimrc`

2. Create the following directory structure in your HOME directory:

```
.vim/
 ├── autoload/
 ├── backup/
 ├── colors/
 └── plugged/
```
`mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged`

3. Copy file contents of `vimrc` from this repository into the new `.vimrc` file.

`cp configs/vimrc ~/.vimrc`

4. Copy all other files from this repository into their respective directories.

`cp -r configs/vim ~/.vim`

5. Open Vim (or any vim file) and install plugins using `:PlugInstall`.

### Color Schemes

**Gotham:** https://github.com/rafi/awesome-vim-colorschemes

**Everforest:** https://github.com/sainnhe/everforest

## IntelliJ IDEA Community

1. Download the Theme plugin you want.

2. Open IntelliJ and open Settings using `⌘,`.

3. In Plugins, click `Intall Plugin from Disk...` and select the Theme plugin file.

4. Select `OK` to apply and save your changes.

### Themes

**Nord:** https://plugins.jetbrains.com/plugin/10321-nord
