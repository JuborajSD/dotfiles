# .vimrc

Custom vim dotfile which supports with some features like VScode has for JavaScript and React.

## Plugins installation

Plugin manager [vim-plug](https://github.com/junegunn/vim-plug), install all the plugins using the following command:

```bash
  :PlugInstall
```

<details>
<summary><strong>Plugins used</strong></summary>

- [vim-color-github](https://github.com/cormacrelf/vim-colors-github)
- [spaceduck](https://github.com/pineapplegiant/spaceduck)
- [vim-startify](https://github.com/mhinz/vim-startify)
- [vim-polyglot](https://github.com/sheerun/vim-polyglot)
- [vim-airline](https://github.com/vim-airline/vim-airline)
- [ale](https://github.com/dense-analysis/ale)
- [coc-nvim](https://github.com/neoclide/coc.nvim)
- [vim-prettier](https://github.com/neoclide/coc.nvim)
- [vim-misc](https://github.com/xolox/vim-misc)
- [vim-colorscheme-switcher](https://github.com/xolox/vim-colorscheme-switcher)
- [nerdtree](https://github.com/preservim/nerdtree)
- [tagbar](https://github.com/preservim/tagbar)
- [vim-css-color](https://github.com/preservim/tagbar)
- [vCoolor](https://github.com/KabbAmine/vCoolor.vim)
- [rust](https://github.com/rust-lang/rust.vim)
- [emmet](https://github.com/mattn/emmet-vim)
- [vim-languagetool](https://github.com/dpelle/vim-LanguageTool)
- [nerdcommenter](https://github.com/preservim/nerdcommenter)
- [vim-easy-align](https://github.com/junegunn/vim-easy-align)
- [sparkup](https://github.com/rstacruz/sparkup)
- [vim-fugitive](https://github.com/tpope/vim-fugitive)
- [vim-gitgutter](https://github.com/airblade/vim-gitgutter)
- [rainbow_parentheses](https://github.com/frazrepo/vim-rainbow)
- [vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors)
- [comfortable-motion](https://github.com/yuttie/comfortable-motion.vim)
- [vim-webdevicons](https://github.com/ryanoasis/vim-devicons)
- [vim-gutentags](https://github.com/ludovicchabant/vim-gutentags)
- [bracey](https://github.com/turbio/bracey.vim)

</details>
</h2>

## Some configurations

For **coc-nvim** to work with these following extensions:

- es7-react-js-snippets
- path-intellisense

**Build these extension packages**
Open terminal and navigate to .config\coc\extensions\node_modules folder then to extensions individual folder and run the following command:

```bash
npm run compile
```

Then replace the following line of code inside package.json of individual extensions:

```json
 "engines": {
   "coc":"*"
 }
```

then it's good to run.

## Thank you!
