sndup-linux
===========

A client, written in bash, to easily upload files to the sndup.net service.
Written by Storm Dragon: http://stormdragon.us/
Released under the terms of the WTFPL: http://wtfpl.net

Usage:
sndup (in X will open a zenity file selection dialog). After the upload completes the link info will be displayed. If you have xclip installed, the download link is placed in the clipboard.
sndup filename (if file exists) uploads the file and shows the info.
sndup -d filename (if file exists) uploads the file and shows the download url with no other text.
