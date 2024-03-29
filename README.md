# Vim for Workman
## YNEO Mod

This is a vimrc to use with the Workman keyboard layout that keeps the direction keys in the original QWERTY locations (under the right hand).

I did this for Colemak first, but I think the final layout on Workman works much better.

<p align="center">
 <img src="https://raw.githubusercontent.com/drewherron/workman-vim/main/workman-vim-yneo.png" width="50%" height="50%">
 <br>
 (Click to enlarge)
 </p>

### What's different:
#### The four direction keys are on y/n/e/o, in the same place as QWERTY's h/j/k/l
- N (shift + ↓) goes to next search match (replaces n)
- E (shift + ↑) goes to previous search match (replaces N)
- Y (shift + ←) moves cursor to top of screen (same location as QWERTY, different letter)
- O (shift + →) moves cursor to bottom of screen (same location as QWERTY, different letter)

#### End of word is on the J key
- J/j replaces E/e
- The keys for next word (W), previous word (B), and end of word (J) are all next to each other.

#### Open new line is on the L key
- L/l replaces O/o
- **L** for **l**ine?

#### Yank is on the K key
- K/k replaces Y/y
- Yan***k***? Or ***k***opy?

#### Help is lower-case h
- replaces K
- Makes sense
#### Join lines is upper-case H
- Replaces J
- Makes less sense

I am providing this here as a vimrc file, but it's probably easier to just paste the following lines into your own vimrc:

```
noremap Y H
noremap y h
noremap N n
noremap n j
noremap E N
noremap e k
noremap O L
noremap o l
noremap H J
noremap h K
noremap J E
noremap j e
noremap K Y
noremap k y
noremap L O
noremap l o
```
