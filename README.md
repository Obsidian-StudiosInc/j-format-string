# jFormatString
[![License](http://img.shields.io/badge/license-GPLv3-9977bb.svg?style=plastic)](https://github.com/Obsidian-StudiosInc/jem/blob/master/LICENSE)
[![Build Status](https://img.shields.io/travis/Obsidian-StudiosInc/jFormatString/master.svg?colorA=9977bb&style=plastic)](https://travis-ci.org/Obsidian-StudiosInc/jFormatString)
[![Build Status](https://img.shields.io/shippable/59c954d374e9b807005d8e33/master.svg?colorA=9977bb&style=plastic)](https://app.shippable.com/projects/59c954d374e9b807005d8e33/)

Source code and tagged source code releases. Continuation of the 
archived [Google Code Project](https://code.google.com/archive/p/j-format-string/)

This code is designed to allow for compile time checking of Java format 
strings. It can check that the format string is valid, that the proper 
number of arguments are supplied and that they are of the correct type.

This code is used by [SpotBugs](https://github.com/spotbugs/spotbugs) 
aka [FindBugs](https://github.com/findbugsproject/findbugs) and if 
offered for use by other tools.

The code for this is derived from the OpenJDK implementation of 
java.util. Authored by [Bill Pugh](https://github.com/billpugh)
