[GORUC](http://go.ruc.edu.cn) CLI
=================================

[![Build Status](https://travis-ci.org/abuccts/goruc-cli.svg?branch=master)](https://travis-ci.org/abuccts/goruc-cli)
[![Code Climate](https://codeclimate.com/github/abuccts/goruc-cli/badges/gpa.svg)](https://codeclimate.com/github/abuccts/goruc-cli)
[![GitHub version](https://badge.fury.io/gh/abuccts%2Fgoruc-cli.svg)](https://badge.fury.io/gh/abuccts%2Fgoruc-cli)
[![GPLv3 licensed](https://img.shields.io/badge/license-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0-standalone.html)

Command line interface for *go.ruc.edu.cn* login/logout

Introduction
------------
Goruc-cli is used to login/logout ruc gateway in command line interface. If you meet the following situations:

* Need to connect to Internet in a linux server without GUI in ruc
* Your computer in the lab is offline and you don't want to/can't go to the lab to login
* You want your computer to login or logout automatically in a script

then you can use goruc-cli to login/logout ruc gateway.

> Note: If you're not in ruc campus, you need to `ssh` to another computer which has Internet access in ruc first, then `ssh` to your target from there.

Issues
------

* Use [goruc-cli issues on GitHub](https://github.com/abuccts/goruc-cli/issues) for open issues

Installation
------------

``` sh
$ git clone https://github.com/abuccts/goruc-cli.git
$ cd goruc-cli
$ chmod u+x goruc
$ sudo ln -s "$(pwd)"/goruc /usr/local/bin
```

Usage
-----
| Command  | Description |
| ------------- | ------------- |
| `goruc -i`  | login  |
| `goruc -o`  | logout  |
| `goruc -h`  | help  |
