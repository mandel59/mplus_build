# mplus_build
working directory for building of [M+ outline fonts](http://mplus-fonts.osdn.jp/mplus-outline-fonts/index-en.html)

# How to build

CVS and FontForge are required. (You can install them with HomeBrew for OS X.)

```
% git clone git@github.com:mandel59/mplus_build.git --recursive
% cd mplus_build
% MPLUS_FULLSET=y make -j4 SPLIT_CONCURRENCY=4
(Enter empty password when asked. SVG files are fetched from the CVS repository.)
% make release
```
