# HEN and CFW Features

HEN and CFW, unlocks a tons of features and I will explain a few of them.

This page is for both routes, but read before performing. Steps may varies if you’re on HEN or CFW.


## Custom Firmware & Cobra Tools

If you're in CFW pretty much everything you might think doing on your PS3 is in XMB's Network tab under **"★ Custom Firmware Tools"**, for HEN you can use apps like multiMAN.


🧭 Table of Contents

- **[🗃️ Acessing PS3 files](#-accessing-ps3-files)**
    - [FTP Server](#ftp-server)
    - [Apps](#apps)
- **[💿 Dump Games](#-dump-games)**
    - [Once a Time](#once-a-time)
    - [File Manager](#file-manager)
    - [Copying Dumped Games](#Copying-Dumped-Games)
- **[🎮 Controllers (PS3XPAD)](#-controllers-ps3xpad)**
- **[🔓 NTFS Drives](#-ntfs-drives)**


# 🗃️ Accessing PS3 files

You can access your PS3 files in two ways. FTP, or through apps.

Note: if you’re on HEN you need to have an app that allows, like multiMAN.


## FTP Server
### CFW

If you’re on CFW you can use “Cobra Tools” (Located on Network column) to enable a tons of features, one of them is FTP.


### HEN

If you’re on HEN you can use multiMAN app, in it settings there’s an option to enable it.


## Apps
### CFW

If you’re on CFW you can use “Cobra Tools” (Located on Network column) it has a tons of features, one of them is accessing PS3 files. But you can only delete or copy files through it.

If you want like a desktop environment, you can use multiMAN’s file manager. (multiMAN settings)


### HEN

If you’re on HEN you can use multiMAN app, in it settings there’s an option to use a file manager.


# 💿 Dump Games

Dumping games both for CFW and HEN are the same way using multiMAN app. But there’s two ways, one if you want to dump only one game. And the other if you want to dump multiple games at once.


## Once a time

Go to the game you want and click /\ (Triangle) button on it. And select “Copy” and then select your USB Flash Drive.


## File Manager

This method allows you to dump multiple games at once. Simply go to multiMAN settings, and launch the file manager.

- Go to this directory: `dev_hdd0\GAMES` if your games are on “JB Folder” format.
- Go to this directory: `dev_hdd0\PS3ISO` if your games are on “ISO” format.
- Go to this directory: `dev_hdd0\game` if your games are on “PKG” format.

Simply copy the games you want to your USB Flash Drive.


## Copying Dumped Games

Saving a PS3 dumped games is a good way to save space, if you want to return them in it place to play them again simply either Go to the game you want and click /\ (Triangle) button on it. And select “Copy”, or 

- Go to this directory: `dev_hdd0\GAMES` if your games are on “JB Folder” format, and copy your game here.
- Go to this directory: `dev_hdd0\PS3ISO` if your games are on “ISO” format, and copy your game here.
    - Or install it if you dumped it as a PKG file.


# 🎮 Controllers (PS3XPAD)

If you want to add more controllers support to your PS3 like: XBOX 360, DualShock 4, then install this plugin.

1. Download this **[ZIP-file for CFW](https://github.com/ZHassanQ/PS3-Guide/releases/download/Others/PS3XPAD-0.8-CFW.zip)**, or this **[ZIP-file for HEN](https://github.com/ZHassanQ/PS3-Guide/releases/download/Others/PS3XPAD-HEN.zip)**
2. Extract it in your PS3 in `dev_hdd0` folder.
- In `dev_hdd0` there is a file named **"boot_plugins.txt"** edit it and add the line `/dev_hdd0/plugins/ps3xpad/xpad_vsh.sprx`. Also in `dev_hdd0/plugins` folder should be in it a folder called `ps3xpad`


# 🔓 NTFS Drives

If don't want to use **FAT32** you can use **NTFS** format. But you need to this in **multiMAN** to read an NTFS drive.

1. In multiMAN, mmCM select **"Switch to multiMAN mode"** in **"multiMAN"** column
2. In **"multiMAN"** column select **"PFS Driver"**
