My AOSP
=====================

Getting Started: Nexus 9
---------------

To build My AOSP from source, you'll need to be familiar with
[Git and Repo](https://nathanpfry.com/how-to-setup-ubuntu-16-04-lts-xenial-xerus-to-compile-android-roms/).


To initialize your local repository, use this command:

	repo init -u https://github.com/USBhost/My-AOSP-manifest.git -b O

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) lunch ## choose flounder

    "make otapackage -j12" like that

