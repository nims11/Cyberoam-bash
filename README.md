cr-client: A Cyberoam BASH Client
===============================

A simple Cyberoam Client in BASH to easen up login/logout activities under Linux

Requirements
------------
* BASH
* curl

Installation
------------
```bash
$ git clone
$ cd Cyberoam-bash
```
Configuration
-------------

The default config file is "config", under the same directory.
Each line of config specifies a config option. Following are possible configuration options
```
# Specify Cyberoam Server
server https://172.16.1.1:8090
# Specify a Profile (Profile name should be anything other than "server")
myID be12342045 pass123
```
You can also configure few other script parameters by checking out the initial lines of the script itself

Usage
-----
```bash
$ ./cr-client -h
Usage:
	cr-client login <profile>
	cr-client login <username> <password>
	cr-client logout
	cr-client -h
	cr-client --help
```

