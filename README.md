# vim-trello
Vim plugin for [Trello](https://trello.com/)

## Installation
### vim-plug
```vim
Plug 'yoshio15/vim-trello', { 'branch': 'main' }
```

## Setting
set your [api key and token of Trello](https://trello.com/app-key) in your vimrc.
```vim
" Trello API Key
let g:vimTrelloApiKey = '{your api key}'
let g:vimTrelloToken = '{your token}'
```

## Usage
```vim
:VimTrello
```
you can open your boards list of trello assosiaded with your Trello account by this command.  

## Key Map
| key | action |
| --- | ------ |
| a | add new card |
| q | close buffer |
| d | delete a card |

## Author
Yoshio Kondo
