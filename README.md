# Shotgun-Version-Upload
This is a Shotgun API script based on the upload script found in the Shotgun API GitHub. The modification allows for automation of Version upload and linking of Project, Shot, Task Status and Playlist. This is also my very first attempt at Python programming, so it's not elegent since I'm not familiar with all the syntax. Please let me know if you find it helpful. Meza Hsu

## Requirements
* Python
* Shotgun API

## Naming of the Version
This is how the script can figure out what to do with the Version
* Seperator is "_" (underscore)
* Pipeline Code
* Episode Number
* Shot Code
* Version Number

## Changelog

**v1.0 - 2015.07.23**

  + Uploads a Version to a Shotgun instance
  + Creates a daily review Playlist, if one does not exist
  + Adds the uploaded version to the daily review Playlist
  + Use Episode Number to link to Project
  + Use Shot Code to link to Shot
  + Use Version Number to create Version
