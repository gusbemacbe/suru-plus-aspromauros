<p align="center"> 
  <img src="logotype.png" alt="Title" height="256px" width="256px">
</p>

<h2 align="center">Suru++ Asprómauros</h2>

<p align="center">
  <img alt="apps" src="https://img.shields.io/badge/apps_icons-5200%2B-01e074.svg?style=plastic?&colorA=4C5561"/>
  <img alt="actions" src="https://img.shields.io/badge/actions_icons-1800%2B-01e074.svg?style=plastic?&colorA=4C5561"/>
  <img alt="devices" src="https://img.shields.io/badge/devices_icons-150%2B-01e074.svg?style=plastic?&colorA=4C5561"/>
  <img alt="mimetypes" src="https://img.shields.io/badge/mimetypes_icons-1100%2B-01e074.svg?style=plastic?&colorA=4C5561"/>
  <img alt="panel" src="https://img.shields.io/badge/panel_icons-1900%2B-01e074.svg?style=plastic?&colorA=4C5561"/>
  <img alt="places" src="https://img.shields.io/badge/places_icons-1300%2B-01e074.svg?style=plastic?&colorA=4C5561"/>
</p>

These aspromautic or monochromatic icons are based on Andrea Bonnani's [Suru++ [Minimal]](https://github.com/Magog64/SURU-PLUS) icons of sizes 16, 24 and 32. It is flat, minimalist and designed for dark environments. 

The word "Asprómauros" comes from the modern Greek word *ασπρόμαυρος*, which means *black and white*.

## Installation

The good news is that, you are no longer required to depend on Sam Hewitt's and other Suru++ packs.

### AUR (for Arch Linux and Arch-based distributions)

```shell
pacaur -Ss suru-plus-aspromauros-git
yaourt -Ss suru-plus-aspromauros-git
yay -Ss suru-plus-aspromauros-git
```

### PPA (Ubuntu and Debian-based distributions)

I am working with the bugs of PPA

### Installation without CLI

* [For users of Ubuntu 16.04 and any old versions of any distributions](instructions_without_cli1.md)
* [For users of Ubuntu 16.04.4, Ubuntu 18.04, Kali Linux and latest versions of any distributions](instructions_without_cli2.md).

### Installation with CLI

* [For users of UBuntu 16.04.4 and any old versions of any distributions](instructions_with_cli1.md)
* [For users of Ubuntu 16.04.4, Ubuntu 18.04, Kali Linux and latest versions of any distributions](instructions_with_cli2.md)

## Known bugs

### Some icons are not correctly applied in some apps

Some apps, as AppImage-buit, Flatpak-built, Snap-built and dpkg-installed apps do not use the relative path of an icon. They use the absolute path of an icon, preventing the icon of being correctly applied. Besides, some apps misuse the icon name, for example, GitHub Desktop uses the icon name called `Icon=desktop`.

We provide desktop files (AppImage, native Debian packages, snap app and source codes) for you for being able of applying correctly the icons. You can download them from the repository  <a href="https://github.com/gusbemacbe/suru-plus/tree/master/desktop">Suru++</a>. Copy them to `your_name/local/applications/`, so they won't be reverted to original when you make next updates of Ubuntu and/or PPAs.

We recommend you to back your desktop configuration files up when you intend to make a clean install or reinstall your distribution.

## Report

* Do you find the missed icons?
* Do you find the misused icons?
* Did you find the errors?

Report, PLEASE fill these WELL-DETAILED informations. IT IS REQUIRED OR WE CAN'T PROVIDE! 😠

## Contribution

* Would you like to improve our repository?
* Do you want to add and request the icons? Make a pull request and we will analyse and approve or not

## Contributors

The contributors is on the file [AUTHORS](AUTHORS)

## Changelog

The changelog is available on the release page in theme's repository.

## Donation

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=gusbemacbe%40gmail%2ecom&lc=BR&item_name=Suru%2b%2b%20Project&item_number=SURU2018GBRC&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted">Donate here</a>

## License

GPL3 © Suru++ Asprómauros by Andrea Bonanni and Gustavo Costa.
