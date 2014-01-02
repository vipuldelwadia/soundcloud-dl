# CLI Souncloud music downloader

## Description
This shell script is able to download music from http://www.soundcloud.com.
It should work with iOS, OS X, Linux, Android(terminal emulator).

## System requirements
* Unix like OS with a proper shell
* curl or wget


## Instructions
* apply executable permissions ```chmod +x ./scdl.sh```
* usage: ```scdl.sh [TRACK(S) URL]``` or ```soundcloud_new.sh [USER URL]``` or ```soundcloud_new.sh [SET(S)URL]```

## Features
* Download all song of one user's page
* Download all song of one song page
* Download all song of one user's playlist page
* Download all song of one user's list of playlist page
* Set tags with id3v2 (skip the tag if id3v2 is not installed
* The script stop when he see one song that have already been downloaded

##TODO
* clean the project, remove old scripts and keep one working instance  -- > Done !
* improve instructions and README --> Done !

## License
[GPL v2](https://www.gnu.org/licenses/gpl-2.0.txt), orignal author [Luka Pusic](http://pusic.si)
