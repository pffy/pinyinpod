# pinyinpod

> # **NOTE:** Please use [pbjkit][pbjkit]. This repo is archived and unmaintained. It simply references an outdated (and poorly-designed) project called *pinyinpod*


# What's new in `pbjkit`

  + [Pinyinbase][pb] and pbjkit are two independent projects now
  + Pinyinbdase now only describes the dictionary source glossaries
  + "Pinyinbase schema" will now be generally described as metapinyin
  + Pinyinbase can be (just-in-time) compiled with pbjkit into CEDICT files
    + EXAMPLE: Using pbjkit to [build new PBDICT][pbdict] from Pimyinbase source with GitHub Actions 
  + pbjkit comprises more than one command line tool for simplicity
  + pbjkit works with `xargs` and other Linux commands



---
[pb]: https://github.com/pffy/pinyinbase
[pbdict]: https://github.com/pffy/pbdict
[pbjkit]: https://github.com/pffy/pbjkit
