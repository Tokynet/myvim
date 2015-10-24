## Clone it
```
git clone https://github.com/Tokynet/myvim.git ~/.vim
```

## Create sym-links
```
ln -s ~/.vim/vimrc ~/.vimrc
```

## Download all modules for first time

```
cd ~/.vim
git submodule update --init
```


## To update all the modules (later)

```
git submodule foreach git pull origin master
```
