# ugit

A mili git replicate in python3

---

### Description

> This projects goal is to replicate git with its basic functionality in python. It created a pip library that can edited locally using develop mode 

### Install

Have the basic files (setup.py and the dir ugit with cli.py) and run:
> python3 setup.py develop --user

This will install the pip package locally and have it linked to edit the files so you can run the commands :

```
ugit init
ugit hash-object txt.txt
ugit get-object sha1hash
ugit etc...
```

### Features done so far:
 - init
 - hash-object
 - cat-object
 - write-tree
 - read-tree
 - commit 
 - log
 - checkout (Branching time~!)
 - tag (wip)

https://www.leshenko.net/p/ugit/