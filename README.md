Souncloud music downloader
==============

Description
--------------
This shell script is able to download music from http://www.soundcloud.com.
It should work with iOS, OS X, Linux.

System requirements
--------------
* nix like OS with a proper shell
* URL (Highly recommended) or wget
* ools wich are preinstalled on linux (I don't know  for OS X) : `recode` ; `sed` ; `tail` ; `tr` ; `echo` ; `grep` ; `head` ; `cut` ; `sort` ; `uniq` .


Install instruction for linux and required tools
--------------
* Update the package list : `sudo apt-get update`
* Install eyeD3 `sudo apt-get install eyeD3`
* Install cURL `sudo apt-get install curl`

Instructions
--------------
* apply executable permissions `chmod +x ./scdl.sh`
* usage: `scdl.sh [TRACK(S) URL]` or `scdl.sh [USER URL]` or `scdl.sh [SET(S)URL]`

Features
--------------
* Download all song of one user's page
* Download all song of one song page
* Download all song of one user's playlist page
* Download all song of one user's list of playlist page
* Set tags with eyeD3 (skip the tag if eyeD3 is not installed)
* The script stop when he see one song that have already been downloaded
* You can use it as a sync script as i do with my Raspberry PI, each night it launch the script with my users profile and if new song as been added it download them and stop when it encounter a song that is already downloaded ;).

Changelog
--------------
18/01/2014 :
* Replacde id3v2 with eyeD3 wich support image tag
* Added image & genre tags support for each type 
* Added support of playlist in an users page !

More information
--------------
The script cannot handle letters like `û` cause to recode. But if i remove it, instead of `&` you will have `&amp;` (the html code of `&`) and as i think there is more `&` than `û` i prefer to let it...

License
--------------
[GPL v2](https://www.gnu.org/licenses/gpl-2.0.txt), orignal author [Luka Pusic](http://pusic.si)
