## Description

Japanese transration of the hdparm's manpage (hdparm.8)
written in [po4a](http://po4a.alioth.debian.org/) format.

## How to make Japanese manpage

1. Install po4a
2. Make ./original/man8 directory
3. Put english hdparm.8 to ./original/man8
4. execute:
   `po4a-translate -f an -m original/man8/hdparm.8 -p hdparm.ja.po -l hdparm.8`
