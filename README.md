# Dotfiles for my Raspberry Pis

I have multiple Raspberry Pis. These files help configure them so that they all operate the same way (at least for bash).

I pulled the contents of this directory from all over the internet. I try to refer to the resources that I used whenever I can.

To download:
```bash
git clone https://github.com/garrettj403/rpi-dotfiles.git ~/.dotfiles
 ```

To install:
```bash
sh ~/.dotfiles/link.sh
cat ~/.dotfiles/append-to-bashrc.txt >> ~/.bashrc
```

Guides:
   - http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/
   - https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789

Examples:
   - https://github.com/thenovices/dotfiles.
