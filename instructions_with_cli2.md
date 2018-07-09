# Installation with CLI

## For users of Ubuntu 16.04.4, Ubuntu 18.04, Kali Linux and latest versions of any distributions

Firstly, you must have `git` and `svn` installed. 

```shell
sudo apt install curl git subversion wget
```

We replace Git for SVN and recommend strongly SVN, which is quicker like a Millennium Falcon than Git. 

```shell
# If the folder icons doesn't exist
mkdir ~/.local/share/icons
# Download quickly like a Millennium Falcon
svn export https://github.com/gusbemacbe/suru-plus-dark/trunk/ ~/.local/share/icons/Suru++\ Dark
# To update the next latest changes and to overwrite
svn export --force https://github.com/gusbemacbe/suru-plus-dark/trunk/ ~/.local/share/icons/Suru++\ Dark
```
