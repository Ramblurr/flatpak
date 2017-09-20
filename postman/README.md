# Postman flatpak

> Postman: https://getpostman.com

### Build Requirements

You need these for building the package

* [flatpak](http://flatpak.org/) - flatpak and flatpak-builder
* [jq](https://stedolan.github.io/jq/) - only way to do json in bash
* [moreutils](https://joeyh.name/code/moreutils/) - for the great sponge util

### Usage

**Check for update**
```
./update
```

**Download update**
```
./update download
```

**Build update**
```
./update download build
```

**Install update**

```
flatpak install ./postman-X.Y.Z.flatpak
```

**Run postman**

```
postman
```
