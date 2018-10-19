SerialCommand
=============
A Wiring/Arduino library to tokenize and parse commands received over a serial port. 

additional usage for using custom serial object.

* With default (Serial)
```Arduino
#include <SerialCommand.h>
SerialCommand parser;
```
* With Custom Serial
```Arduino
#include <SerialCommand.h>
SerialCommand parser(Serial2);
```
* With Custom Serial, and custom debug
```Arduino
#include <SerialCommand.h>
#define SERIALCOMMAND_DEBUG
SerialCommand parser(Serial2, Serial3);
```

The original version of this library was written by [Steven Cogswell](http://husks.wordpress.com) (published May 23, 2011 in his blog post ["A Minimal Arduino Library for Processing Serial Commands"](http://husks.wordpress.com/2011/05/23/a-minimal-arduino-library-for-processing-serial-commands/)).

This is a heavily modified version with smaller footprint and a cleaned up code by Stefan Rado.
