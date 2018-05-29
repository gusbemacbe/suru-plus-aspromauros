# Installation with CLI

## For users of old Ubuntu versions, Ubuntu 16.04 and any Debian-derived distributions

Firstly, you must have `git` and `svn` installed. 

```shell
sudo apt install curl git subversion wget
```

We replace Git for SVN and recommend strongly SVN, which is quicker like a Millennium Falcon than Git. 

```shell
# If the folder icons doesn't exist
mkdir ~/.icons
# Download quickly like a Millennium Falcon
svn export https://github.com/gusbemacbe/suru-plus-dark/trunk/ ~/.icons/Suru++\ Dark
# To update the next latest changes and to overwrite
svn export --force https://github.com/gusbemacbe/suru-plus-dark/trunk/ ~/.icons/Suru++\ Dark
```