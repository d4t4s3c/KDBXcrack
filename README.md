### KDBXcrack

![GitHub stars](https://img.shields.io/github/stars/d4t4s3c/KDBXcrack?logoColor=yellow) ![GitHub forks](https://img.shields.io/github/forks/d4t4s3c/KDBXcrack?logoColor=purple) ![GitHub watchers](https://img.shields.io/github/watchers/d4t4s3c/KDBXcrack?logoColor=green)</br>
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/d4t4s3c/KDBXcrack) ![GitHub contributors](https://img.shields.io/github/contributors/d4t4s3c/KDBXcrack)

### Overview

This tool is ideal if you are unable to crack a master password from a [KeePass](https://keepass.info/) database due to incompatibility with version 4.x with [keepass2john](https://github.com/openwall/john/blob/bleeding-jumbo/src/keepass2john.c) and it displays the following error:

>! database.kdbx : File version '40000' is currently not supported!

![](screenshot.png)

### Download

```sh
wget --no-check-certificate -q "https://raw.githubusercontent.com/d4t4s3c/KDBXcrack/refs/heads/main/KDBXcrack" && chmod +x KDBXcrack
```

### Usage

```cmd
KDBXcrack -f <FILE> -w <WORDLIST>
```

### Dependencies

- keepassxc-cli
