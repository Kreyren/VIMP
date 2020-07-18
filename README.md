# Vim

## General
`X` -> number value. All of these commands can work with multiple times. i.e `5` + `dd`.
* `h` -> move left (cursor)
* `j` -> move down (cursor)
* `k` -> move up (cursor)
* `l` -> move right (cursor)
* `q`, `quit`, `x`, `exit` -> quit vim
* `SHIFT` + `ZZ` -> Quit
* `!` -> don't save changes. (example: `q!`)
* `w`, `write` -> write changes
* `gg` -> takes to the first line (cursor)
* `shift` + `G` -> takes to the last line (cursor)
* `i` -> insert mode (to type text)
* `ESC` -> gets into normal mode (with delay of 1s)
* `ESC ESC` -> gets into normal mode immediately
* `v` -> visual mode (to select texts)
* `0` -> takes cursor to the first character in a line
* `x` -> to delete a character
* `u` -> to undo
* `d` + `w` -> to delete a word
* `dd` -> Delete a line
* `w` -> goes forward to the next word (first character)
* `e` -> goes forward to the next word (last character)
* `w` -> goes backwords to the previous word (first character)
* `p` -> puts the deleted line of chars in the next line where cursor is (i.e `10` + `dd` + `p`)
* `r` + `X` -> to replace a character with X
* `c` + `e` -> deletes characters till end aka a word for replacement with new characters
* `c` + `$` -> deletes the entire line for replacement with new characters
