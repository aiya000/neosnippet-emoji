# :gift: neosnippet-emoji :gift:

This allows you and Vim to input emoji characters via [neosnippet.vim](https://github.com/Shougo/neosnippet.vim).

💪😎👍

![sample](./sample.gif)

## Why this is useful?

In many contexts, we cannot use `:github-flavor-style-emojis:`. (e.g. filetype: `text`, (common) `markdown`, `tweetvim_say`.)
But we want to use emojis.

This allows you to use emojis in the contexts!

## Installation

- 1. Download this into your local (or either add as a submodule or clone this repository)

```shell-session
$ curl https://raw.githubusercontent.com/aiya000/neosnippet-emoji/master/neosnippets/emoji.snip -o ~/.vim/neosnippets/emoji.snip
```

- 2. Link it to a filetype you need

For example, if you use `let g:neosnippet#snippets_directory='~/.vim/neosnippets'`

```shell-session
$ cd ~/.vim/neosnippets
$ mkdir filetype_you_need  # if needed
$ cd $_
$ ln -s ~/.vim/neosnippets/emoji.snip .
```

- :+1:. Now you can use this!
