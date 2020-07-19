# Useful Vim Key Bindings

All keybinds are available in `vimtutor` and in `help`, this is short summary for personal use

## Keybind phonesis
- `q` - Quit
- `y` - Yank (Used to copy)
- `c` - Cut
- `u` - Undo
- `!` - Force
- `v` - Visual
- `w` - Write
- `X` - Encypt
- `i` - Insert
- `b` - Back
- `p` - Paste

## Modes

Vim modes changes the behavior on keybind press

### Normal mode

To enter the normal mode from any mode press:
* `ESC` -> gets into normal mode (with delay of 1s)
* `ESC ESC` -> gets into normal mode 

### Insert mode

To enter the insert mode from normal mode press `i` or `INSERT_KEY`

### Replace mode

FIXME-DOCS

## Code navigation

In normal mode:

* `h` - move left (cursor)
* `j` - move down (cursor)
* `k` - move up (cursor)
* `l` - move right (cursor)
* `w` - goes forward to the next word (first character)
* `e` - goes forward to the next word (last character)
* `b` - goes backwords to the previous word (first character)

## Saving the code

- `:w` - Write changes
- `:w!` - Forced write
  - Used to write changes in read-only files

- `:x` - Save and exit
- `:x!` - Forced save and exit
  - Used to write changes in read-only file

## Copy

In normal mode use `v` for visual mode and select the part you want to copy then press `y`

## Cut

In normal mode use `v` for visual mode and select the part you want to copy then press `c`

## Paste

In normal mode use `p`

## How to exit

In normal mode use `:q` to exit

In normal mode use `:q!` to exit without saving changes

When in doubt or panic `xkill` or removing the power plug from the wall also works

## Character replacing

* `r` + `X` -> to replace a character with X
* `c` + `e` -> deletes characters till end aka a word for replacement with new characters
* `c` + `$` -> deletes the entire line for replacement with new characters

## Useful actions

In normal mode:

* `gg` -> takes to the first line (cursor)
* `shift` + `G` -> takes to the last line (cursor)
immediately
* `v` -> visual mode (to select texts)
* `0` -> takes cursor to the first character in a line
* `x` -> to delete a character
* `d` + `w` -> to delete a word
* `dd` -> Delete a line
