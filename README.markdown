# Souncloud music downloader v3.2

Contributors: lukapusic <luka@pusic.si>, ivanov, elboulangero <elboulangero@gmail.com>  
URI: http://360percents.com/posts/soundcloud-com-music-downloader-linux-and-mac/  
Github: https://github.com/lukapusic/soundcloud-dl

## Description
Shell script to download music from http://www.soundcloud.com.
Supports multiple pages.

## System requirements
* Unix like OS
* wget or curl

## Instructions
* apply executable permissions ```chmod +x ./soundcloud.sh```
* usage: ```soundcloud.sh [DJ-URL]```

## Changelog

###v3.0
* won't fail if the artists landing page isn't tracks (removed in v3.1)
* supports multiple page downloading

###v3.1
* now supports downloading of private songs

###v3.2
* properly handle more than 10 pages
* resumes partial downloads, so you don't re-download already downloaded files

###Oct 10 2012
* applied http://pastebin.com/ZG5JD1Em patch to fix page number issues

## Known issues
* will fail if the artists landing page isn't tracks again, but on purpose

## License
* ----------------------------------------------------------------------------
* CC-BY-NC, Luka Pusic
* ----------------------------------------------------------------------------
