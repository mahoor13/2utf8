# 2utf8
Convert any .srt file with any encoding to utf-8 encoding

To run this file you need python 2+ and python chardet library

## Install pip on ubuntu:
sudo apt-get update && sudo apt-get install -y git python-pip

## Install chardet:
```
pip install --upgrade pip
pip install chardet
```

## Installation:
```
git clone git://github.com/mahoor13/2utf8
chmod a+x ./2utf8/2utf8
cp ./2utf8/2utf8 /usr/local/bin/
```

## usage:
```
2utf8 # shows the help
2utf8 a-movie-subtitle.srt # converts a-movie-subtitle.srt to utf-8 encoding. Output name is the same as movie file or current .srt file .bak file will be create if needed
2utf8 a-movie-subtitle.srt utf8.srt # converts a-movie-subtitle.srt to utf-8 encoding output name utf8.srt
```
