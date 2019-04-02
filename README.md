AOSGP E Guide:-
============

• Also available in Spanish [**here**]()

-----------------------------------------------------------------------------

Getting Started:
===============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize this repository in local, use this command:

```bash
    repo init -u https://github.com/aosgpe/manifest -b android-9.0.0_r34
```

Then to sync up:
================

```bash
    repo sync
```

Additionally, you can define the number of parallel download repo should do to decrease waiting time:

```bash
    repo sync -f -jX ( X is the number of parallel download repo should do choose depending on your cpu )
```

How to compile AOSGP E:
======================

From downloaded directory of Project, perform following commands in terminal:


```bash
source build/envsetup.sh
lunch treble_<CPU arch>_<type of partition>-userdebug
make -jX (X is the number of parallel process you can do simultaneous, normally is double of your cpu's theards)
```

Guide to treble compile:
======================

• All this guide is extracted from [GSI build](https://source.android.com/setup/build/gsi#downloading-gsis)

• CPU's Arch type:
	• ARM for 32 bit phone
	• ARM64 for 64 bit phone
	
• Type of partition:
	• agN for phones with no transparent updates
	• bgN for phones with transparent updates
	• You can check this with [*this app*](https://play.google.com/store/apps/details?id=com.kevintresuelo.treble&hl)

-----------------------------------------------------------------------------

Social Networks:-
============
* [**Website**](http://aosgp.org/ethernumen)
* [**Youtube**](https://www.youtube.com/channel/UCYjJT5cjGLqjt1C_YWxIrgg)
* [**Twitter**](https://twitter.com/aosgp)

Downloads:
=========

[![Download AOSGP E 1.x - P](https://aosgp.org/ethernum/wp-content/uploads/sites/2/2019/04/11954334231297714979molumen_download_button_1.svg)](https://downloads.aosgp.org/)

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**phhusson**](https://github.com/phhusson?tab=repositories)