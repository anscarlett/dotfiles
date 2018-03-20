# dotfiles repo administered using dotdrop

Steps to install

1. create a place to put your dotfiles
2. initialise the directory as a git repository
3. install dotdrop as git submodule
4. install dotdrop requirements
5. initialise dotdrop

```bash
$ mkdir dotfiles; cd dotfiles
$ git init
$ git submodule add https://github.com/deadc0de6/dotdrop.git
$ sudo pip3 install -r dotdrop/requirements.txt
$ ./dotdrop/bootstrap.sh
```

6. add dotfiles to dotdrop config
7. add all files to repository

```bash
$ ./dotdrop.sh import ~/.vimrc ~/.tmux.conf ~/.tmux.zenburn.conf ~/.vim/
$ git add .
$ git commit -m "initial commit"
``` 
8. Create a new repository on github
9. synchronise local reporitory with github
10. push everything to the new repository
```bash
$ remote add origin https://github.com/anscarlett/dotfiles.git
$ git push origin master
```

