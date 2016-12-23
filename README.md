# curlbash

Sanity check your curlbash installers before running them. This will display the
contents of the script and allow the user to decide whether it should be run or not.

## Usage

This script takes the place of bash in a curlbash install script
and attempts to sanitize it a bit. For example, replace

     curl http://example.com/installer | bash

with

     curl http://example.com/installer | curlbash

## Installation

1. Download the script
1. Place it in your path
    * e.g. `mv curlbash /usr/local/bin/`
1. Make it executable
    * e.g. `chmod +x /usr/local/bin/curlbash`
1. Profit
