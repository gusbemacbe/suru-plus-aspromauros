# Installation with CLI

## For users of Ubuntu 16.04 and any old versions of any distributions

Firstly, you must have `git` and `svn` installed. 

```shell
sudo apt install curl git subversion wget
```

We replace Git for SVN and recommend strongly SVN, which is quicker like a Millennium Falcon than Git. 

```shell
# If the folder icons doesn't exist
mkdir ~/.icons
# Download quickly like a Millennium Falcon
svn export https://github.com/gusbemacbe/suru-plus-aspromauros/trunk/ ~/.icons/Suru++\ Asprómauros
# To update the next latest changes and to overwrite
svn export --force https://github.com/gusbemacbe/suru-plus-aspromauros/trunk/ ~/.icons/Suru++\ Asprómauros
```