# MuscleCard-Applet
The Muscle Applet is a free implementation of the Cryptographic Card Edge Definition for Java Enabled Smartcards.


INTRODUCTION
========
It is capable of generating cryptographic keys on the card, and allows external keys to be inserted onto the card. These keys can be used in cryptographic operations, after proper user (or host application) authentication. 

This Applet is capable of handling generic objects. 

An object is a sequence of bytes whose meaning is determined by the application. The Applet allows a host application to read and/or modify objects’ contents, after proper user (or host application) authentication. 

License 
=======
The source code is released under BSD and is free.

Discussion
=======

Have doubts? You can visit [Here](http://javacardos.com/javacardforum/viewforum.php?f=40?ws=github&prj=muscleCard) to get more scripts and leave your comments and suggestions.

Building
===

The easiest way is using [JCIDE](http://javacardos.com/javacardforum/viewtopic.php?f=26&t=43?ws=github&prj=muscleCard) open this project,  Click "Buid All Packages(F7)" to build the source code.

Usage:
===========
 Use [pyApduTool](http://javacardos.com/javacardforum/viewtopic.php?f=3&t=38?ws=github&prj=muscleCard) to Download this  applet to card, install, select and communicate with the card.


Additional Features:
=========
This Applet actually supports some pin policy enforcement.
Checks are made on the pin size, character set and mix of characters.
The exact pin policy depends on parameters provided at instantiation time.

Note:
======
Different versions of this Applet could be released, with different features disabled, in order to let you save space on the card if your application does not require those features at all.

