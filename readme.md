#archive-dl
A small script to download live shows from archive.org. It should work on "streaming only" sjpws as well.

## Installation
You will first need to download the script to a directory in your PATH. On my Fedora system that is ~/bin. Then you need to make the script executable. So for fedora do:

```bash
cd ~/bin
wget https://github.com/rdingram/archive-dl/raw/master/archive-dl
chmod 755 archive-dl
```

## Usage

The script takes one argument, the url of the show you would like to download. Here is an example using the Grateful Dead's concert at Barton Hall on 5/8/1977.

```bash
archive-dl https://archive.org/details/gd1977-05-08.shure57.stevenson.29303.flac16
```

The script will then begin downloading each track of the concert in mp3 format in the current working directory.

## Issues

Well seeing as how this is a really dirty barebones script hobbled together at 2AM there will probably be ~75% success rate. I plan on taking this idea and expanding on it greatly since there appears to be a need for something like this.

If you do have issues please file an issue in the the repo and maybe we can workk together to remedy it.
