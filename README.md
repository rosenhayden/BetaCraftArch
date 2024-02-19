# BetaCraft for Arch Linux
A short guide on how to get beta craft working on Arch Linux

![screen](https://github.com/rosenhayden/BetaCraftArch/assets/91492781/922a6f92-02d3-4ae4-9321-e854246a7c71)

## Download the BetaCraft Launcher

**Go to** *https://betacraft.uk/downloads* 

Download the middle **.JAR** option

## Install Java 8

* $ sudo pacman -S jre8-openjdk

## Run the launcher

* $java -jar ~/Downloads/launcher-1.09_16.jar

If you want you can move the jar with dolphin or the mv command to another directory. Just make sure that you point there then using this command. 

## Optional: Add an Alias

Add and alias to your zsh or bash rc so you don't have to type that long command to open the launcher.

* $ nvim ~/.zshrc

add something like: *alias ANYWORDSHERE='~/Downloads/launcher-1.09_16.jar'* 

Don't forget to change the location in the alias if you moved the jar file.
## Version and Name

Select the version you want with the *Select version* tab. Example: 1.7.3

Add a player name, it's local so it can be whatever.

**Launch The Game with the *Play* button**

![mc_map_0000](https://github.com/rosenhayden/BetaCraftArch/assets/91492781/55c363ff-733a-482e-b61a-2de6e451ed0b)
