# CLI Souncloud music downloader

## Description
This shell script is able to download music from http://www.soundcloud.com.
It should work with iOS, OS X, Linux.

## System requirements
* Unix like OS with a proper shell
* cURL (Highly recommended) or wget
* Tools wich are preinstalled on linux (I don't know  for OS X) : recode ; sed ; tail ; tr ; echo ; grep ; head ; cut ; sort ; uniq.


## Install instruction for linux and required tools
* Update the package list : ````sudo apt-get update````
* Install id3v2 ````sudo apt-get install id3v2````
* Install cURL ````sudo apt-get install curl````

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
* You can use it as a sync script as i do with my Raspberry PI, each night it launch the script with my users profile and if new song as been added it download them and stop when it encounter a song that is already downloaded ;).

##TODO
* clean the project, remove old scripts and keep one working instance  -- > Done !
* improve instructions and README --> Done !

## More information
The script cannot handle letters like û cause to recode. But if i remove it instead of & you will have &amp; (the html code of &) and as i think there is more & than û i prefer to let it...

## License
[GPL v2](https://www.gnu.org/licenses/gpl-2.0.txt), orignal author [Luka Pusic](http://pusic.si)
