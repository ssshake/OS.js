# OS.js on Intel Edison

Just follow the manual installation docs and you should be able to run without any problems.

**NOTE** Installing on *vfat* sdcards is causing some problems with `npm` packages. Any other linux-based filesystem seems to work just fine.

If you want to use git, follow this guide to install the `git` package: https://github.com/w4ilun/edison-guides/wiki/Installing-Git-on-Intel-Edison

**An official package will be made for this purpose later**

## Make your own image

```
./bin/build-opkg.sh osjs 2.0.0-0001 all intel-edison
```