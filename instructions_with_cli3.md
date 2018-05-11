# Installation with CLI

## For users of Ubuntu 16.04.4 and above, Kali Linux and any new Debian-derived distributions.

You do not need to download and install Sam Hewitt's Suru Icon, because it already comes installed under Ubuntu 18.04 and above.
The icon pack Suru++ is important to be included because it is inherited by Suru++ Dark.

Firstly, you must have `git` and `svn` installed. 

```shell
sudo apt install curl git subversion wget
```

Choose one of two options — Git or SVN. We recommend strongly SVN, which is quicker than Git. 

### Git

```shell
# If the folder icons doesn't exist
mkdir ~/.local/share/icons
# You need to enter in the icons folder to download the icons pack
cd ~/.local/share/icons
# Download the icon pack...
git clone https://github.com/Magog64/SURU-PLUS.git
git clone https://github.com/Magog64/SURU-PLUS-DARK.git
# To update the next latest changes
git pull origin master 
```

You do not need to download and install Sam Hewitt's Suru Icon, because it already comes installed under Ubuntu 18.04 and above

```shell
# If the folder icons doesn't exist
mkdir ~/.local/share/icons
# Download quickly like a Millennium Falcon
svn export https://github.com/Magog64/SURU-PLUS/trunk/ ~/.local/share/icons/Suru++
svn export https://github.com/Magog64/SURU-PLUS-DARK/trunk/ ~/.local/share/icons/Suru++\ Dark
# To update the next latest changes and to overwrite
svn export --force https://github.com/Magog64/SURU-PLUS/trunk/ ~/.local/share/icons/Suru++
svn export --force https://github.com/Magog64/SURU-PLUS/trunk/ ~/.local/share/icons/Suru++\ Dark
```
