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

