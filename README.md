﻿# onscripter-jh-gpm280z2
[WIP] My ONScripter-jh Waveshare GPM280Z2 port

## Bugs, TODO    
* button (key) input not good  

## Prebuild  
$ sudo apt-get install libsdl1.2-dev libsdl-image1.2-dev libsdl-mixer1.2-dev libsdl-ttf2.0-dev libsdl-gfx1.2-dev liblua5.1-0-dev libbz2-dev libfontconfig1-dev libavifile-0.7-dev libsmpeg-dev  

## Build and Run  
* make -f Makefile.Linux  
* see https://github.com/weimingtom/wmt_rpi_study/tree/master/onscripter-jh  
$ tar xzf onscripter-jh.tar.gz  
$ unzip onscripter_cn_test.zip  
$ cd onscripter-jh  
$ make -f Makefile.Linux  
$ cd ../onscripter_cn_test  
$ ../onscripter-jh/onscripter  

## WinSCP SSH copy files     
* pi/raspberry  

## Ref  
* https://blog.csdn.net/AGrapier/article/details/50378531  
* (dead) https://bitbucket.org/jh10001/onscripter-jh/src/1eb517e6406488697e3a215f0d2817f0bc524c85/?at=default  
* https://www.waveshare.net/wiki/GPM280Z2  

## (TODO) key???
```
B=305  
A=304  
Y=308  
X=307  
START=315  
SELECT=314  
L=310  
R=311  
```
