# Own AUR

AUR registration is closed, so I'll build my own AUR. With blackjack and hookers!

In fact, forget the blackjack and hookers.

Use at your own risk.

## Usage
Put
```toml
[own-aur]                                                                                                                                                         
Url = https://github.com/a-gal/own-aur.git
```
into your `~/.config/paru/paru.conf` and run
```shell
paru -Sy --pkgbuilds
```

## Updating/Adding New Packages To This Repo
Run
```shell
makepkg --printsrcinfo > .SRCINFO
```
after updating PKGBUILD to update metadata
