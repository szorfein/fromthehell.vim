# fromthehell.vim

vim colorscheme

You need [Vundle](https://github.com/gmarik/vundle) or [Pathogen](https://github.com/tpope/vim-pathogen/):

### vundle

Edit `~/.vimrc` to add:

```txt
Plugin 'szorfein/fromthehell.vim'
```
And run into vim:

    :PluginInstall

### Pathogen

    $ mkdir -p ~/.vim/bundle
    $ cd ~/.vim/bundle
    $ git clone https://github.com/szorfein/fromthehell.vim

## Configuration

Just edit your `~/.vimrc` to add:

    syntax on
    colorscheme fromthehell

The background color use your terminal bg, so you may use this: (e.g for kitty)

    background #2b161c

---

![Screenshot](https://raw.githubusercontent.com/szorfein/fromthehell.vim/master/screenshot.jpg "screenshot")

### Links
+ [show all the 256 vim colors](http://www.calmar.ws/vim/256-xterm-24bit-rgb-color-chart.html)
+ [theme generator devify](http://bytefluent.com/devify/)
