# dlplus
DeskLink+ is a Tandy Portable Disk Drive emulator or "TPDD Server" implimented in C.

[Original README](README.txt)

[Documentation for DeskLink](dl.do)

Original source: <http://bitchin100.com/files/linux/dlplus.zip>

## news
Added -b option for "bootstrap"

To install teeny* on the Model 100, just run
    dl -b
This essentially takes the place of teeny-linux|teeny-freebsd|teeny-macosx

This just sends LOADER.DO to the M100.  
The default included LOADER.DO containes a loader for "teeny",  
but you may replace LOADER.DO with another one to install something else like "tiny" or "dskmgr" or possibly even ts-dos etc.
