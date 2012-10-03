# Souncloud music downloader v3.2

Contributors: [lukapusic](https://github.com/lukapusic), [ivanov](https://github.com/ivanov), [elboulangero](https://github.com/elboulangero)  
URI: http://360percents.com/posts/soundcloud-com-music-downloader-linux-and-mac/  
Github: https://github.com/lukapusic/soundcloud-dl

## Description
This shell script is able to download music from http://www.soundcloud.com.
It downloads music from all relevant artist pages and it has been tested on iOS, OS X, Linux.
OS X users and other that don't have wget installed should use curl version.

## System requirements
* Unix like OS
* wget or curl

## Instructions
* apply executable permissions ```chmod +x ./soundcloud.sh```
* usage: ```soundcloud.sh [DJ-URL]```

## Changelog

###Dec 16, 2010
* Initial version released on [360percents.com](http://360percents.com/posts/soundcloud-com-music-downloader-linux-and-mac/).

###May 15, 2011
* supports multiple page downloading

###Nov 13, 2011
* now supports downloading of private songs

###Jul 17, 2012
* properly handle more than 10 pages
* resumes partial downloads, so you don't re-download already downloaded files

###Oct 10, 2012
* applied http://pastebin.com/ZG5JD1Em patch to fix page number issues

##TODO
* Check if user has curl or wget installed and use the right one.
* Merge the wget and curl version of the script and make it more user friendly.

## Known issues
* will fail if the artists landing page isn't tracks

## License
[CC-BY-NC](https://creativecommons.org/licenses/by-nc/2.0/), [Luka Pusic](http://pusic.si)