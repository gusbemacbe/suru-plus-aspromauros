# Installation with CLI

## For users of Ubuntu 16.04.4 and above, Kali Linux and any new Debian-derived distributions.

You download three icon packs - Sam Hewitt's Suru Icon, Suru++ and Suru++ Dark. 
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
# As you are an user of old Ubuntu versions, Ubuntu 16.04 and any Debian-derived distributions, you must install firstly Sam Hewitt's Suru Icons
git init ~/.local/share/icons
git remote add -f origin https://github.com/snwh/suru-icon-theme
git config core.sparseCheckout true
echo "Suru" >> .git/info/sparse-checkout
git pull origin master
# Download then two icon packs...
git clone https://github.com/Magog64/SURU-PLUS.git
git clone https://github.com/gusbemacbe/SURU-PLUS-DARK.git
# To update the next latest changes
git pull origin master 
```

### SVN

```shell
# If the folder icons doesn't exist
mkdir ~/.local/share/icons
# As you are an user of before Ubuntu 16.04 and above, you must install firstly Sam Hewitt' Suru Icons
svn export https://github.com/snwh/suru-icon-theme/trunk/Suru/ ~/.local/share/icons/Suru
# Download quickly like a Millennium Falcon
svn export https://github.com/Magog64/SURU-PLUS/trunk/ ~/.local/share/icons/Suru++
svn export https://github.com/gusbemacbe/SURU-PLUS-DARK/trunk/ ~/.local/share/icons/Suru++\ Dark
# To update the next latest changes and to overwrite
svn export --force https://github.com/Magog64/SURU-PLUS/trunk/ ~/.local/share/icons/Suru++
svn export --force https://github.com/gusbemacbe/SURU-PLUS-DARK/trunk/ ~/.local/share/icons/Suru++\ Dark
```
