![Iceberg](https://cocopon.github.io/iceberg.vim/assets/github/title.png)




Overview
--------
Iceberg is a dark blue color scheme for Vim. It brings a cool-headed perspective
for your happy coding!

![Screenshot](http://cocopon.github.io/iceberg.vim/assets/github/screenshot.png)

![Palette](https://cocopon.github.io/iceberg.vim/assets/github/palette.png)

See the [official site](http://cocopon.github.io/iceberg.vim/) or the
[vimonline page](http://www.vim.org/scripts/script.php?script_id=4820) for more
information.




Features
--------
- 256-colors terminal support
- [airline][airline] theme and [lightline][lightline] colorscheme
- Various plugins support:
  [ALE][ale]
  / [CtrlP][ctrlp]
  / [Denite][denite]
  / [EasyMotion][easymotion]
  / [Git Gutter][git-gutter]
  / [Signify][signify]
  / [Sneak][sneak]
  / [Startify][startify]
  / [Syntastic][syntastic]
  / [vim-plug][vim-plug]
  / [vim-zenspace][vim-zenspace]
  etc.
- Better syntax highlight with:
  [typescript-vim][typescript-vim]
  / [vim-flow][vim-flow]
  / [vim-graphql][vim-graphql]
  / [vim-javavscript][vim-javascript]
  / [vim-markdown][vim-markdown]
  etc.
- [Neovim][neovim] terminal colors support




Philosophy
----------
Creator of Iceberg talked about how to create your lovely color scheme in [VimConf 2017][vimconf2017], international Vim conference. [This presentation][vimconf-presentation] also explained the philosophy of Iceberg.

[![Creating Your Lovely Color Scheme](http://cocopon.github.io/iceberg.vim/assets/github/creating-your-lovely-color-scheme.png)][vimconf-presentation]




Building your own Iceberg
-------------------------
1. Install [cocopon/pgmnt.vim][pgmnt], a template engine for Vim color scheme, to your Vim.

2. To modify a color palette, edit `autoload/iceberg/palette/dark.vim`. If you 
   make changes, be sure to `:source` this file before step 4 otherwise your color
   palette changes will not be reflected.

3. To modify highlighting groups or links, edit `src/iceberg.vim`.

4. After editing, compile the source file as below:

    ```vim
    :e src/iceberg.vim
    :cd %:h
    :source %
    ```

    Compiled files will be output into `autoload` directory.




For other environments
----------------------
- [Terminal.app profile](https://cocopon.github.io/iceberg.vim/#macosTerminalApp) by [cocopon](https://github.com/cocopon)
- [iTerm2](https://github.com/aseom/dotfiles/blob/master/osx/iterm2/iceberg.itermcolors) by [aseom](https://github.com/aseom)
- [Atom](https://github.com/cocopon/atom-iceberg-syntax/) by [cocopon](https://github.com/cocopon)
- [Xcode](https://github.com/cocopon/xcode-iceberg) by [cocopon](https://github.com/cocopon)
- [AppCode](https://github.com/Kuniwak/iceberg.icls) by [Kuniwak](https://github.com/Kuniwak)

NOTE: [terminal.sexy][terminal-sexy] provides configuration files for
the 16 ANSI colors for many terminal emulators. Use [.Xresources file][xresources]
as import and export it for the emulator of your choice.




License
-------
MIT License. See `LICENSE.txt` for more information.




[ale]:https://github.com/w0rp/ale
[airline]:https://github.com/vim-airline/vim-airline/
[ctrlp]:https://github.com/ctrlpvim/ctrlp.vim
[denite]:https://github.com/Shougo/denite.nvim
[easymotion]:https://github.com/easymotion/vim-easymotion
[git-gutter]:https://github.com/airblade/vim-gitgutter
[lightline]:https://github.com/itchyny/lightline.vim
[neovim]:https://neovim.io/
[pgmnt]:https://github.com/cocopon/pgmnt.vim
[signify]:https://github.com/mhinz/vim-signify/
[sneak]:https://github.com/justinmk/vim-sneak
[startify]:https://github.com/mhinz/vim-startify
[syntastic]:http://github.com/vim-syntastic/syntastic
[terminal-sexy]:http://terminal.sexy
[typescript-vim]:https://github.com/leafgarland/typescript-vim
[vim-flow]:https://github.com/flowtype/vim-flow
[vim-graphql]:https://github.com/jparise/vim-graphql
[vim-javascript]:https://github.com/pangloss/vim-javascript
[vim-markdown]:https://github.com/tpope/vim-markdown
[vim-plug]:https://github.com/junegunn/vim-plug
[vim-zenspace]:https://github.com/thinca/vim-zenspace
[vimconf-presentation]:https://speakerdeck.com/cocopon/creating-your-lovely-color-scheme
[vimconf2017]:http://vimconf.vim-jp.org/2017/
[xresources]:https://gist.github.com/cocopon/1d481941907d12db7a0df2f8806cfd41
