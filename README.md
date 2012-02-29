## Description

This is a Vim version of the IR_Black color scheme, created by Todd Werth as described [here](http://blog.toddwerth.com/entries/8), and ever so slightly modified by me.

I've been using this excellent color scheme for a few years, but now I'm starting to get bothered by the fact that I keep it in source control with my dotfiles, and can't just load it with [pathogen](https://github.com/tpope/vim-pathogen), so I'm putting it here - feel free to include it as a submodule, clone it or fork it.

---

## Installation

In your vimrc, add

```
set background=dark
syntax enable " syntax highlighting
colorscheme ir_black
```

### with pathogen

Simply clone this repository into your pathogen bundle folder (for example ~/.vim/bundle).
For example: `git clone git://github.com/promisedlandt/vim-colors-ir_black.git ~/.vim/bundle`

### without pathogen

Create a `colors` directory in your vim preferences folder (for example ~/.vim/colors).

Clone the repository into a temporary path, then copy `colors/ir_black.vim` to your newly created `colors` directory.

---

## Screenshots

Please see Todd Werth's [original blog post](http://blog.toddwerth.com/entries/8) for screenshots.

