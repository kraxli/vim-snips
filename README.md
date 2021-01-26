# vim-snips
[Ultisnips](https://github.com/sirver/UltiSnips) snippets for neovim / vim

## Set Variables
```vim
  g:signature
  g:dir_screenshots
```

## Using snippets for your filetypes
Put e.g. the follwing into you `.vimrc` or your `init.vim` after loading [SirVer/ ultisnips](https://github.com/sirver/UltiSnips)

```vim
    UltiSnipsAddFiletypes vimwiki.markdown
    UltiSnipsAddFiletypes vimwiki.writer
    UltiSnipsAddFiletypes tex.writer
    UltiSnipsAddFiletypes markdown.writer
```

# Snippets
use `./file_na<tab>` or `file_nam<c-f>` to let pop up the selection list. To complete or expand sections of a file, use `[link](file_name#sec<c-o>)`

`linkHyp` snippet: insert file name (for completion use `<c-f>`) and  use `#<c-o>` for section completion
