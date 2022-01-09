# Linux File System

**FHS: Filesystem hierarchy standart**

## bin
  - binaries
  - basic command line binaries

## sbin
  - system binaries

## boot
  - dont play around here!
  - boot loader folder
  
## cdrom
  - its legacy anymore

## dev
  - devices
  - eveerything is a file in linux
  - every devices has a file here

## etc
  - all configs are stored
  - system wide configs

## home
  - every user has its home folder
  - application settings
  - most known subfolders:
    - /home/.cache
    - /home/.config

## lib
  - libraries stored
  - required by /bin or /sbin
  
## media
  - mounted devices
  - usb stick 
  - os managed
  
## mnt  
  - mounted devices
  - user managed

## opt
  - optional folder
  - software packages etc.

## proc
  - dont play here!
  - processes
  - sudo files
  - all running processes
  - ex: /proc/cpu
  
## root
  - root user's home folder
  - root permission is required to see

## run
  - tempfs file system
    
## snap
  - snap packages folder
  
## srv
  - service data directory
  - web server, ftp server files etc.
  
## sys
  - system folder
  - interacts with kernel
  - created everytime system boots up

## tmp
  - temporary directory
  - empty when reboot
  
## usr
  - user application space
  - most known subfolders:
    - /usr/share
    - /usr/local

## var
  - variable directory
  - files expected to increase 
  - log, db files etc.
  
