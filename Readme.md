# Mycomment

My work is to convert the mappings to other keys, not to conflict with cscope mappings

_A stupid comment plugin made for people can't remember so many mappings:)_

You only need to remember one mapping for comment:  `<leader>x`

## Install

Use your favourite plugin manager add something like `Bundle 'chemzqm/mycomment.vim'`

## API

### [count]\<leader\>xc

Toggle comment of `count`(default current line) lines.

### \<leader\>xip

Toggle comment of a block. Yes, it's a motion mapping, `ip` could be any motion object.

### V\*\*\*\<leader\>x

Select a block and toggle comment

## More productive

You can use `.` to repeat your last comment command, no need [vim-repeat](https://github.com/tpope/vim-repeat).

If you have [emmet-vim](https://github.com/mattn/emmet-vim), the plugin would use emmet comment function for comment toggle of tags in html/xml/xhtml files

## License

MIT
