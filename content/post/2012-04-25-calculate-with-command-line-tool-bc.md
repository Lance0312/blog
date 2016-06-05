+++
title = "Calculate with command-line tool bc"
date = "2012-04-25T23:57:00+08:00"
type = "post"
tags = ["Cli"]
+++

Basic usage
```bash
$ echo 'expr' | bc
```
  
Hex to Dec
```bash
$ echo 'ibase=16;obase=A;FF' | bc
255
```
