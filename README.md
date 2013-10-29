eslpod-catcher
==============

ESL Podcast downloader. Get all free MP3 files from http://eslpod.com

Why
---

[English as a Second Language Podcast](http://eslpod.com) is a great resource for people learning English. Unfortunately,
there is no easy way to download all MP3s at once. Old and new episodes are in separate podcasts.

**Full ESL Podcast is about 15GB of MP3s as of October 2013.**

Usage
-----

```
./eslpod-catcher
```

This will create **ESLPod.txt** file with the list of all MP3s and download them to **ESLPod** folder. To update podcast
later just run the command again. It only downloads new or changed files.

Installation
------------

```
git clone https://github.com/vlazar/eslpod-catcher.git
cd eslpod-catcher
bundle
```

Prerequisites
-------------

* [Ruby](https://www.ruby-lang.org)
* [Bundler](http://bundler.io)
* [Wget](http://www.gnu.org/software/wget)
