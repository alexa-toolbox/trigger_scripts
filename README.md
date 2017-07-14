# Trigger scripts from Alexa


## Setup Vagrant
```bash
$ vagrant init ubuntu/trusty64
```

Add shared folder


Create a virtual python environment
```bash
$ virtualenv alexa --python=python2
```
Activate virtual environment
```bash
$ . alexa/bin/activate
```

Install Setup Tools
```bash
$ pip install setuptools
```

Install Git Repository
```bash
$ cd fork_echo
$ pip install -r requirements.txt
```
