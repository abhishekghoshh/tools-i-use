# terminal helper

## Youtube video and channels
- **mac**
  - [50 macOS Tips and Tricks Using Terminal (the last one is CRAZY!)](https://www.youtube.com/watch?v=qOrlYzqXPa8)
- **linux**
  - [7 Essential Command Line Tools (2022)](https://www.youtube.com/watch?v=2OHrTQVlRMg)
  - [5 Linux Terminal Applications You Need](https://www.youtube.com/watch?v=E8Ww39z_28A)
- **mac & linux**
  - [6 AWESOME Command Line Tools For MAC And LINUX](https://www.youtube.com/watch?v=szehPBOwqlI)
  - [7 Amazing CLI Tools You Need To Try](https://www.youtube.com/watch?v=mmqDYw9C30I)
- **windows**
  - [Make Windows Terminal look amazing!](https://www.youtube.com/watch?v=AK2JE2YsKto)
  - [Make Windows Terminal Look Better | Oh My Posh Guide](https://www.youtube.com/watch?v=-G6GbXGo4wo)
- **channels**
  - [typecraft](https://www.youtube.com/@typecraft_dev/playlists)


## fzf
- [FZF Will CHANGE How You Work](https://www.youtube.com/watch?v=MvLQor1Ck3M)

## Password manager
- [This is perhaps my favorite password manager for the terminal](https://www.youtube.com/watch?v=FhwsfH2TpFA)

## Tmux
- [Tmux is more than just a splitting terminal](https://www.youtube.com/watch?v=MLDmM_zRl40)
- [Tmux has forever changed the way I write code.](https://www.youtube.com/watch?v=DzNmUNvnB04)
- [TMUX and Terminal configuration](https://www.youtube.com/playlist?list=PLsz00TDipIfct4F3pHv6_uI9OyjphQEGZ)
- [I made the greatest tool ever! | tmux & cht.sh & fzf](https://www.youtube.com/watch?v=hJzqEAf2U4I)
- [My Developer Workflow - How I use i3, tmux, and vim](https://www.youtube.com/watch?v=bdumjiHabhQ)
- [How I Use Tmux With Neovim For An Awesome Dev Workflow On My Mac](https://www.youtube.com/watch?v=U-omALWIBos)
- [My AMAZING Terminal Setup - Hyper, Oh My Zsh, Fig.io, and More!](https://www.youtube.com/watch?v=SyOnB1qvPn0)
- [This plugin makes you a Vim and TMUX GOD](https://www.youtube.com/watch?v=qyV_hOtMdwg)
- [you need to learn tmux RIGHT NOW!!](https://www.youtube.com/watch?v=nTqu6w2wc68)
- [How To Make Your Boring Mac Terminal So Much Better](https://www.youtube.com/watch?v=CF1tMjvHDRA)
- [Learn tmux](https://www.youtube.com/playlist?list=PLT98CRl2KxKGiyV1u6wHDV8VwcQdzfuKe)
- [Tmux Tutorial for Beginners](https://www.youtube.com/watch?v=U41BTVZLKB0)
- [Tmux From Scratch To BEAST MODE](https://www.youtube.com/watch?v=GH3kpsbbERo)
- [Tmux for Newbs. FREE TMUX COURSE](https://www.youtube.com/playlist?list=PLsz00TDipIfdrJDjpULKY7mQlIFi4HjdR)


## Zellij
- [zellij](https://zellij.dev/)





## bash shortcuts


```
# kill active process, stops the current in-progress command
# Kill whatever you are running. Also clears everything on current line
ctrl + c

# Exit the current shell when no process is running, or send EOF to a the running process
ctrl + d


# minimize/suspend the current process and come back to the terminal, put process in background
ctrl + z

# reopen the background process, foreground
fg

# list of background jobs
bg

# show the current jobs
job


# Up arrow shows previous commands


# clear your screen
ctrl + l / cmd + k




# Tab automatically completes commands




# set the cursor to the first letter/start in the command line, go to front of the line
ctrl + a

# set the cursor to the last letter/end in the command line, go to end of the line
ctrl + e

# go forward one character
ctrl + f

# go backword one character
ctrl + b 

# Move cursor one word forward, jump forward by one word
alt + f   /   Option + →

# Move cursor one word backward, jump backward by one word
alt + b   /   Option + ←



# Swap the last two characters before the cursor (not working in mac, it is showing a list of files as fuzzy finder)
ctrl + t

# Swap the last two words before the cursor
esc + t



# Cut everything backwards to beginning of line, delete the line in the command prompt
ctrl + u

# to remove the word backwards from cursor position
ctrl + w

# Cut one word backwards using none alphabetic characters as delimiters
esc + backspace

# Cut everything forward to end of line, to delete the line starting from the cursor position
ctrl + k 

# to delete a word starting from the current cursor position
alt + d

# delete one character
ctrl + h

# Paste whatever was cut by the last cut command, to paste text from the kill buffer
ctrl + y

# Undo the last command. (Underscore. So it's actually Ctrl + Shift + minus)
ctrl + _  (Ctrl + Shift + minus)


```




# mac terminal helper

## Work with Terminal windows and tabs
```
# New window
cmd + n

# exit a window
exit

# New window with same command
Control-Command-N

# New tab
cmd + t

# New tab with same command
Control-Command-T

# Show or hide tab bar
Shift-Command-T

# Show all tabs or exit tab overview
Shift-Command-Backslash (\)

# New command
Shift-Command-N

# New remote connection
Shift-Command-K

# Show or hide Inspector
Command-I

# Edit title
Shift-Command-I

# Edit background colour
Option-Command-I

# Make fonts bigger
Command-Plus (+)

Make fonts smaller

Command-Minus (-)

Next window

Command-Grave Accent (`)

Previous window

Command-Shift-Tilde (~)

Next Tab

Control-Tab

Previous Tab

Control-Shift-Tab

Split window into two panes

Command-D

Close split pane

Shift-Command-D

Close tab

Command-W

Close window

Shift-Command-W

Close other tabs

Option-Command-W

Close all

Option-Shift-Command-W

Scroll to top

Command-Home

Scroll to bottom

Command-End

Page up

Command-Page Up

Page down

Command-Page Down

Line up

Option-Command-Page Up

Line down

Option-Command-Page Down
```

## Edit a command line

```
Reposition the insertion point

Press and hold the Option key while moving the pointer to a new insertion point

Move the insertion point to the beginning of the line

Control-A

Move the insertion point to the end of the line

Control-E

Move the insertion point forwards one character

Right Arrow

Move the insertion point backwards one character

Left Arrow

Move the insertion point forwards one word

Option-Right Arrow

Move the insertion point backwards one word

Option-Left Arrow

Delete the line

Control-U

Delete to the end of the line

Control-K

Delete forwards to the end of the word

Option-D (available when Use Option as Meta key is selected)

Delete backwards to the beginning of the word

Control-W

Delete one character

Delete

Forward-delete one character

Forward Delete (or use Fn-Delete)

Transpose two characters

Control-T
```


## Select and find text in a Terminal window

```
Action

Shortcut

Select a complete file path

Press and hold the Shift and Command keys and double-click the path

Select a complete line of text

Triple-click the line

Select a word

Double-click the word

Select a URL

Press and hold the Shift and Command keys and double-click the URL

Select a rectangular block

Press and hold the Option key and drag to select text

Cut

Command-X

Copy

Command-C

Copy without background colour

Control-Shift-Command-C

Copy plain text

Option-Shift-Command-C

Paste

Command-V

Paste the selection

Shift-Command-V

Paste escaped text

Control-Command-V

Paste escaped selection

Control-Shift-Command-V

Find

Command-F

Find next

Command-G

Find previous

Command-Shift-G

Find using the selected text

Command-E

Jump to the selected text

Command-J

Select all

Command-A

Open the character viewer

Control-Command-Space
```

## Work with marks and bookmarks
```
Mark

Command-U

Mark as bookmark

Option-Command-U

Unmark

Shift-Command-U

Mark line and send return

Command-Return

Send return without marking

Shift-Command-Return

Insert bookmark

Shift-Command-M

Insert bookmark with name

Option-Shift-Command-M

Jump to previous mark

Command-Up Arrow

Jump to next mark

Command-Down Arrow

Jump to previous bookmark

Option-Command-Up Arrow

Jump to next bookmark

Option-Command-Down Arrow

Clear to previous mark

Command-L

Clear to previous bookmark

Option-Command-L

Clear to start

Command-K

Select between marks

Shift-Command-A
```


## Other shortcuts
```
Enter or exit full screen

Control-Command-F

Show or hide colours

Shift-Command-C

Open Terminal settings

Command-Comma (,)

Break

Typing Command-Full Stop (.) is equivalent to entering Control-C on the command line

Print

Command-P

Soft reset terminal emulator state

Option-Command-R

Hard reset terminal emulator state

Control-Option-Command-R

Open a URL

Hold down the Command key and double-click the URL

Add the complete path to a file

Drag the file from the Finder into the Terminal window

Export text as

Command-S

Export selected text as

Shift-Command-S

Reverse search command history

Control-R

Toggle "Allow Mouse Reporting" option

Command-R

Toggle "Use Option as Meta Key" option

Command-Option-O

Show alternate screen

Shift-Command-Down Arrow

Hide alternate screen

Shift-Command-Up Arrow

Open man page for selection

Control-Shift-Command-Question Mark (?)

Search man page index for selection

Control-Option-Command-Slash (/)

Complete directory or file name

On a command line, type one or more characters, then press Tab

Display a list of possible directory or file name completions

On a command line, type one or more characters, then press Tab twice
```


-------------------------------------------------
## zsh terminal specific
```
# create a new tab zsh terminal 
cmd + t

# switch tab in zsh terminal
ctrl + tab    /      ctrl + shift + tab
cmd + left arraow  /   cmd + right arrow
cmd + shift + [     /    cmd + shift + ]

# split the window horizonatally in zsh terminal
cmd + d

# split the window vertically in zsh terminal
cmd + shift + d

switch between splitted tabs 
cmd + [    /     cmd + ]

# close the current tab in zsh terminal
cmd + w
```



