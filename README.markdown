# Souncloud music downloader

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

##TODO
* Check if user has curl or wget installed and use the right one.
* Merge the wget and curl version of the script and make it more user friendly.

## Known issues
* will fail if the artists landing page isn't tracks

## License
[CC-BY-NC](https://creativecommons.org/licenses/by-nc/2.0/), [Luka Pusic](http://pusic.si)
