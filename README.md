Linley's Dungeon Crawl 4.0b26
===============================

This is a modified copy of Linley's Dungeon Crawl 4.0b26 from [ftp.dungeoncrawl.org](http://dungeoncrawl.org/).

The original files are the initial commit of this repository, changes were made to allow compilation on modern systems. So far, compilation is known to work on Mac OS X.

How To Compile
--------------

1. cd to the base dir
2. `sudo mkdir -p /opt/crawl/lib/`, or update `SAVE_DIR_PATH` in `source/AppHdr.h`
3. `./dolinks.sh` (this creates `NORMAL` & `WIZARD` directories)
4. `./domake` (this builds `NORMAL/crawl` and `WIZARD/crawl` (wizmode)
