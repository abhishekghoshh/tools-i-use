# Neovim helper

```
# practice vim motions 

docker run -it --rm -v $(pwd):/mnt busybox vi /mnt/vim-motion-practice.txt
```


- **Vim motions**
  - **blogs**
  	- [shortcutfoo](https://www.shortcutfoo.com/app/dojos/neovim/cheatsheet)
  	- [devhints](https://devhints.io/vim)
  	- [Vim Cheat Sheet](https://vim.rtorr.com/)
  	- [warp.dev](https://www.warp.dev/topic/vim)
  	- [vim-hero](https://www.vim-hero.com/lessons/basic-movement)
  - **youtube**
    - [Vim Motions for absolute beginners!!!](https://www.youtube.com/watch?v=lWTzqPfy1gE)
      - [Intermediate Vim Motions and Pro Tips!!!](https://www.youtube.com/watch?v=nBjEzQlJLHE)
    - [Vim Tips I Wish I Knew Earlier](https://www.youtube.com/watch?v=5BU2gBOe9RU)
      - [10 Advanced Vim Features (You Probably Didn't Know)](https://www.youtube.com/watch?v=gccGjwTZA7k)
    - [Vim As Your Editor](https://www.youtube.com/playlist?list=PLm323Lc7iSW_wuxqmKx_xxNtJC_hJbQ7R)
    - [Vim Tutorial for Beginners](https://www.youtube.com/watch?v=RZ4p-saaQkc)
    - [30 Vim commands you NEED TO KNOW (in just 10 minutes)](https://www.youtube.com/watch?v=RSlrxE21l_k)
  

- **neovim introduction**
  - [PDE: A different take on editing code](https://www.youtube.com/watch?v=QMVIJhC9Veg)
  - [Effective Neovim: Instant IDE](https://www.youtube.com/watch?v=stqUbv-5u2s)
  	- [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim)
  	- [The Only Video You Need to Get Started with Neovim](https://www.youtube.com/watch?v=m8C0Cq9Uv9o)
	- [How I Setup Neovim To Make It AMAZING in 2024: The Ultimate Guide](https://www.youtube.com/watch?v=6pAG3BHurdM)

  
- **all neovim configuration**
    - [Learn Neovim The Practical Way](https://alpha2phi.medium.com/learn-neovim-the-practical-way-8818fcf4830f#545a)

- **Neovim tutorial series**
  - [Teaching Neovim From Scratch To A Noob](https://www.youtube.com/watch?v=-ybCiHPWKNA)
  - [Neovim](https://www.youtube.com/playlist?list=PLOIdWGSU_Wcp9_w8euHJaux8DEIBCvYGc)
	- [Neovim from Scratch](https://www.youtube.com/playlist?list=PLhoH5vyxr6Qq41NFL4GvhFp-WLd5xzIzZ)
	- [Neovim for Newbs. FREE NEOVIM COURSE](https://www.youtube.com/playlist?list=PLsz00TDipIffreIaUNk64KxTIkQaGguqn)
	- [Neovim Configuration](https://www.youtube.com/playlist?list=PLsz00TDipIffxsNXSkskknolKShdbcALR)
	- [Beginner Vim](https://www.youtube.com/playlist?list=PLmTrCsxAaghUhCmSiX5Py-e9O8UOPX502)
	- [Coding With Vim](https://www.youtube.com/playlist?list=PLmTrCsxAaghW9KWrzuc6n2B9ud2uV5sjK)
	- [Bash2Basics](https://www.youtube.com/playlist?list=PLep05UYkc6wTWlugE_9Lj6JlLpvSBbkZ_)
	- [Make a Simple Vim/Neovim Plugin from Scratch: cyclist.vim](https://www.youtube.com/watch?v=apyV4v7x33o&list=PLep05UYkc6wSgBFseCsRBSQQ1Fmf3eRa8)

- **Neovim Customization**
	- [The perfect Neovim setup for Go](https://www.youtube.com/watch?v=i04sSQjd-qo)
	- [The perfect Neovim setup for Rust.](https://www.youtube.com/watch?v=mh_EJhH49Ms)
	- [Setting up Neovim for Java Development](https://www.youtube.com/watch?v=8q_VPqA-KLs)
	- [Effective Neovim setup for web development towards 2024](https://www.youtube.com/watch?v=fFHlfbKVi30)
	- [The Holy Grail of Neovim Git Integrations](https://www.youtube.com/watch?v=K-FKqXj8BAQ)
	- [Automatically Execute *Anything* in Nvim](https://www.youtube.com/watch?v=9gUatBHuXE0)
	- [Execute **anything** in neovim (now customizable)](https://www.youtube.com/watch?v=HlfjpstqXwE)
	- [Neovim - Github Copilot | Setup & Demo | Copilot Creates a Simple Game By Itself | Official Plugin](https://www.youtube.com/watch?v=eMnZBaOs4vM&list=PLhoH5vyxr6Qo_5IoxqcQjHgBe77xD5-BP)
	- [Better than Copilot? This AI plugin for Neovim is Incredible](https://www.youtube.com/watch?v=7k0KZsheLP4)

- **Advance topics**
	- [TakeTuesday E03: Introduction to LuaSnip](https://www.youtube.com/watch?v=Dn800rlPIho)
	- [Why Vim Experts Do THIS Instead of Using Tabs...](https://www.youtube.com/watch?v=ST_DZ6yIiXY)


#### Install neovim with lua-jit
```
sudo apt update && sudo apt upgrade -y
sudo apt install ninja-build gettext libtool libtool-bin autoconf automake cmake g++ pkg-config unzip curl
git clone https://github.com/neovim/neovim.git
cd neovim && git checkout stable
make CMAKE_BUILD_TYPE=Release
sudo make install
echo 'export PATH="$PATH:/path/to/neovim"' >> ~/.zshrc
source ~/.zshrc
```

### Neovim chad
- [Neovim](https://www.youtube.com/playlist?list=PL05iK6gnYad1sb4iQyqsim_Jc_peZdNXf)
- [NeoVim with NVChad | The most beautiful editor for programming.](https://www.youtube.com/watch?v=Irm2WELYSps)
- [Official documentation](https://nvchad.com/docs/quickstart/install)
- [nvchad github](https://github.com/NvChad/NvChad)
- 

- **Shortcuts**
  - Use the Ctrl-^ or (Ctrl-6) shortcut to navigate back to the previously opened file stored in a buffer
  - Use (ctrl + o) to go forward and (ctrl + i) to go back
  - indentation on left and right (v to enter visual mode then press < or >) (but after pressing > it will indent the lines and unselect those, so we can use gb to restore last visual block)
  - leader key is space by default
  - space + c + h for cheetsheet opening and closing
  - only type space bar + wait for 2 sec it, it will suggest some next commands to type
  - Space + t + h (setting themes) [ctrl + p/n for going to previous and next option ]
  - Syntax highlighting [TSInstall #laungage_name] [:TSInstallInfo to check which language syntax highlighting s are installed]
  - Install all packages with mason (:MasonInstallAll)
  - :help lspconfig-all
  - File explorer [cntrl + n] 
    - m for bookmarking
    - a for adding new file
    - c for copy and p for paste file
    - r for renaming a file
    - d for deleting file
    - file navigation ina fuzzy finder (space + ff)
    - space + f + b for find only opened files
  - window management
    - Window navigation [ ctrl + h / j / k / l ]
    - Window management [vertical split (:vsp)  split (:sp)] 
    - Tab change (tab) (shift + tab) and close tab ( space + x )
  - Toggle line number [ space + n ]
  - open terminal
    - Horizontal ( space + h )
    - vertical ( space + v )
    - to get out of terminal or jump to other windows from terminal (ctrl-x then ctrl-ww)
  - others
    - go to normal mode then press :Lazy it will open the LazyVim installer
    - go to normal mode then enter :Mason oe :Lsp and hit tab it will suggest commad, it will work for other any command suggestion
- **customization**
  - neovim configs present in `~/.config/nvim/lua/custom`
    - if you want to change config, plugins and options for neovim chad then change configuration in chadrc.lua
    - id you want to change config, option and commands for neovim only then change configuration in init.lua

### Golang config for neovim
```
Sample go neovim config that I am reffering https://github.com/dreamsofcode-io/neovim-go-config/tree/main
1. Download an lsp server for go (gopls is the official)
  download it with either mason or go get
  add configs

2. Autoformatting on save
  we can either use gopls or use null-ls plugin
  we have null-ls.lua config file where we have added all the formatting related configs
  we have used gofumpt,goimports_reviser, and golines, but we have to install these using go get package name
  go install -v github.com/incu6us/goimports-reviser/v3@latest
  go install github.com/segmentio/golines@latest

  now we have formatting setup and we can call it by (:lua vim.lsp.buf.format())
  but it is hectic to run everytime, so we can turn autoformat on save

  null-ls is having some issues in my local so I have used normal gopls for setting autoformatting

3. now we will setup delve (go install github.com/go-delve/delve/cmd/dlv)
    if delve is unrecognized then use the following line
      export PATH=$PATH:~/go/bin/dlv
      export PATH=$PATH:$(go env GOPATH)/bin
      ~/go/bin/dlv version
  Along with delve we need neovim dap (debug adapter protocoll) we will use nvim-dap-go plugin for that
  to install go grammar for neovim Treesitter use (:TSInstall go)
    <space> + db for debug point
    <space> + dn => :DapStepOver for going to next line
    <space> + dc => :DapContinue for go to the next debug point
    <space> + du for debug ui
    <space> + dgt for running test
    <space> + dgl for running last test
    

4. for extra capabilities we use gopher.nvim (https://github.com/olexsmir/gopher.nvim)
    nvim-dap is required
  see the link for more shortcut
    :GoTagAdd json " For add json tag
    :GoTagRm yaml " For remove yaml tag

    :GoMod tidy " Runs `go mod tidy`
    :GoMod init asdf " Runs `go mod init asdf`
    :GoGet github.com/gorilla/mux

    :GoImpl [receiver] [interface]
    " Also you can put cursor on the struct and run:
    :GoImpl [interface]

    " Example
    :GoImpl r Read io.Reader
    " or simply put your cursor in the struct and run:
    :GoImpl io.Reader

    :GoTestAdd
    :GoTestsAll
    :GoTestsExp

    " Run `go generate` in cwd path
    :GoGenerate
    " Run `go generate` for current file
    :GoGenerate %

    Generate doc comment
    First set a cursor on public package/function/interface/struct and execute:
    :GoCmt

    :GoIfErr
  5. Go to definition
    gd -> go to defination
    gD -> g + shift + d -> go to declaration

```

### rust config for neovim
```
1. first install lsp server for rust(rust-analyser)
  either from mason or from rustup
2. We can add formatting on save capabilities with rust-lang/rust.vim plugin
  It will add autoformatting on save

  copied all the config from https://github.com/dreamsofcode-io/neovim-rust

  install llsb package for debug our code

  This is incomplete

```


### Java config for neovim
```
1. first install jdtls,java-debug-adapter from mason
2. :TSInstall Java -> install treesitter for java
3. 

```


# vim motion cheetsheet

## Things to remember
1. toggle the relative line number, when you want to jump directly to next or previous lines
   1. **in nvchad**
      1. :set rnu
      2. :set nornu
2. Mapping esc to any other key ( caps lock)
3. :normal  (normal mode) change multiple line in the same time
   1. (v 10j) -> :normal Ivar [first select 10 consecutive lines and then insert var at the start]
   2. (v 10j) -> :normal A end; [first select 10 consecutive lines and then append end; at the end]
4. change multiple line in the same time ( from the middle of sentence or at the end )
   1. go to the start of the word then (ctrl + v) then (5l + 10j) then (shift + I) to insert then type your text and press ESC to apply the changes for the next 10 lines
   2. go to the start of the word then (ctrl + v) then (5l + 10j) then (shift + A) to Append then type your text and press ESC to apply the changes for the next 10 lines
   3.**To append a text for the next lines** : (ctrl + v) then press (shift + 4) or $ to selct to the end of the line then use 10 j to select next 10 lines and then (shift + A) to Append and type your changes and press ESC to apply your changes for the next 10 lines.
5. Sometime when we are selecting lines and we forgot the first line then we can use (ctrl + o) which will change the direction of the selecting and select the first line
6. % to go to starting or ending of the parenthesis. We can use it to select the entire content inside those parenthesis, or also we can go to the function


(shift + j) => remove empty lines and append the start of the next line to the end of the current line 


(shift + left arrow) go to the starting of the previous word
(shift + right arrow) go to the starting of the next word

(shift + down arrow) go the ending line of the current page
(shift + up arrow) go the starting line of the current page


#### Jump between lines
Press ( or (shift + 9) to go to the start of previous line
press ) or (shift + 0) to go to the start of next line


#### Jump between paragraphs
Press } or (shift + ] ) to go to the start of previous empty line
Press { or (shift + [ ) to go to the start of next empty line


Press [ to go to the start of the first line
Press ] to go to the start of the last line



ctrl + b to move a page screen back or "up"
ctrl + f to move a page screen front or "down"
ctrl + u to move a ½ page screen up.
ctrl + d to move a ½ page screen down.






#### Command Description	
```
i -> Insert at cursor (goes into insert mode)
a -> Write after cursor (goes into insert mode)
A -> Write at the end of line (goes into insert mode)
ESC -> Terminate insert mode
u ->  Undo last change
U -> Undo all changes to the entire line
o -> Open a new line (goes into insert mode)
d -> Delete line
3dd -> Delete 3 lines
D -> Delete contents of line after the cursor
C -> Delete contents of a line after the cursor and insert new text. Press ESC key to end insertion.
dw -> Delete word
4dw -> Delete 4 words
cw -> Change word
x -> Delete character at the cursor
r -> Replace character
R -> Overwrite characters from cursor onward
s -> Substitute one character under cursor continue to insert
S -> Substitute entire line and begin to insert at the beginning of the line
~ -> Change case of individual character
```




