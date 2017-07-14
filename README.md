# Trigger scripts from Alexa


## Setup Vagrant
$ vagrant init ubuntu/trusty64

Add shared folder


Create a virtual python environment
$ virtualenv alexa --python=python2

Activate virtual environment
$ . alexa/bin/activate

Install Setup Tools
$ pip install setuptools

Install Git Repository
$ cd fork_echo
$ pip install -r requirements.txt

