# ISO Builder

## What does this script do? 

This script lets you create a completely automated Ubuntu Server installation CD (default:18.04.2 64 bit) that you can boot on any PC and have a working server in minutes without ever touching a keyboard.

## How does it do it?

Fuses Ubuntu iso with a [KickStart](http://fedoraproject.org/wiki/Anaconda/Kickstart) file, configures and creates a new ISO file


## How do I run it?

If you're happy with Ubuntu server 18.04.2 64 bit, just download/clone the repository, chdir to it, and run the script:

    ./ubunutu-iso-builder.sh

### Default name and password?

Default username is `user` and password is `pass`. 

## What are the other files in this repo?

3 files are copied onto the CD image:

