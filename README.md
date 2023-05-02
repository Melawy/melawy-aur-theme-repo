# melawy-aur-theme-repo
Linux repo of AUR arch linux theme packages

```bash
sudo pacman-key --recv-keys 95F48000540A4DB146583A47C49B5E77FD80302D --keyserver hkps://keys.openpgp.org
sudo pacman-key --lsign-key 95F48000540A4DB146583A47C49B5E77FD80302D
```

или

```bash
sudo pacman-key --lsign-key 95F48000540A4DB146583A47C49B5E77FD80302D --keyserver http://keyserver2.pgp.com
sudo pacman-key --lsign-key 95F48000540A4DB146583A47C49B5E77FD80302D
```

```bash
sudo pacman -S melawy-linux-mirrorlist
```

Добавить в /etc/pacman.conf

```
[melawy-aur-theme]
SigLevel = Required DatabaseOptional
Include = /etc/pacman.d/melawy-linux-mirrorlist
```

В списке пакетов имеются только пакеты, которые установлены у меня

### Donate
[Tinkoff](https://www.tinkoff.ru/rm/fadeeva.valeriya96/9bLRi79066)

[YooMoney](https://yoomoney.ru/to/4100115921160758)

[Qiwi](https://qiwi.com/n/VALERIAFADEEVA)

Etherium 0x981FBf878fe451BDB83BEaF68078394d4B13213f
