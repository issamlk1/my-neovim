my working neovim settings

my hyperland dot files are 
https://github.com/Hyde-project/hyde

useful snipits for my kitty

this for opening folder with nautilus without warnings.
open() {
    nohup nautilus -w $1 > /dev/null 2>&1 &
}
