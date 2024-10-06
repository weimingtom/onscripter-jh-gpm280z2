# onscripter-jh-gpm280z2
[WIP] My ONScripter-jh Waveshare GPM280Z2 port

## bugs, todo  
* button (key) input not good  

## Prebuild  
$ sudo apt-get install libsdl1.2-dev libsdl-image1.2-dev libsdl-mixer1.2-dev libsdl-ttf2.0-dev libsdl-gfx1.2-dev liblua5.1-0-dev libbz2-dev libfontconfig1-dev libavifile-0.7-dev libsmpeg-dev  

## Build and Run  
$ tar xzf onscripter-jh.tar.gz  
$ unzip onscripter_cn_test.zip  
$ cd onscripter-jh  
$ make -f Makefile.Linux  
$ cd ../onscripter_cn_test  
$ ../onscripter-jh/onscripter  

## WinSCP SSH copy files     
* pi/raspberry  
