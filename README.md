##  Recursive search and replace utility for linux/mac

## Syntax:

   $strswap <search_string> <replace_string> <file_extension, just extension don't prepend with '*' >

	- Don't add "*" in front of file extension, just input .php or .c 

## Example Usage

 	$strswap foo bar .php

	This command recursively search for foo and replace the text with bar in all the php files insided the directory and sub-directories.

## Key Functionalities:

       - Recursively search for text inside files
       - Search all files with the input file extension
       - The tool doesn't touch symbolic link
       - If symbolic link points to a file outsite the directory ( No search/replace operation happen outside the current directory )
       - No backup file will be created, It is the responsibility of the user to take a backup
       - Recursively search all the sub directories

## Useful for:

    - Web Site Admin
    - System Admin


## Installation

	1. Clone this repo
	2. cd src
 	3. ./install.sh




