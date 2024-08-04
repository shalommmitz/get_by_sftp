# Get files or folders using sftp

The motivation to write this software (script?) is that some machines do not offer SCP, but do offer sftp.

Usage is very convenient, as you only have to specify the first letter(s) of the file or folder you want to fetch to the local machine - no need to type the full name.
Also, your input is not case-senstive. If more than one file or folder matches, you can choose which items to fetch, using a menu.

## Installation

This software requires Python3.x and a Linux or similar OS.

Install the liberties:
   
   `pip3 install -r requirements.txt`

## Usage
   
   Usage: ./get_by_sftp \<first letter(s) of file(s) or folder(s) to fetch\> (not case sensitive)

## License:  MIT
