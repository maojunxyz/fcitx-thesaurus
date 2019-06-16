# Fcitx-thesaurus
Input method thesaurus for fcitx

> If you use Doube Pinyin,recommend you use flypy(小鹤双拼).Input away from the cloud.
https://github.com/imaojun/flypy-linux

## How to use
**about**  

- small-thesaurus
Only integrates Sogou lexicon, computer vocabulary and poetry.
- full-thesaurus
Compared with small-thesaurus, it integrates more thesaurus, relatively comprehensive.

**install**

1. Download  thesaurus to local.
use git:
```sh
$ git clone git@github.com:imaojun/fcitx-thesaurus.git
```
or direct download:  
https://github.com/imaojun/fcitx-thesaurus/archive/master.zip

2. Enter one of the folders
Put the files(`pyphrase.mb` and `pybase.mb`) into the *~/.config/fcitx/pinyin* directory.
```sh
$ cp *.mb ~/.config/fcitx/pinyin/
```
3. Reload fcitx.

# Reference link
- [hslinuxextra-Google Code Archive](https://code.google.com/archive/p/hslinuxextra/downloads)
