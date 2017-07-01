# Keylogger
A keylogger for windows, developed as a part of the "Build an Advanced Keylogger using C++ for Ethical Hacking!" course on Udemy.

This keylogger is capable of recording all the keyboard and mouse input! It can even record keystrokes independent of the language settings because it logs the physical keys on the keyboard first. Next, by using an arbitrary keymap with human friendly names, it translates the machine keys to something that we can understand. It also possesses mail sending capabilities so you can just schedule the logfile to be sent via mail, lets say every 12 hours. In addition to this, it will also keep the logfile encrypted.

## Compiler Setting For CodeBlocks:
* added a new flag with the following setting -> Compiler
  * name: windowsAPI
  * Compiler flags: -mwindows
  * linker flags: -mwindows

## Debuging:
* If you wish to use this keylogger you must edit the following lines of codes : 16-18 in SendMail.h.
* Make sure the email account used can support unsecure apps.

## Disclamer:
Using the keylogger to log/record other people's keystrokes or break into another person's computer without his/her knowledge can be considered as an illegal activity. It is the final user's responsibility to obey all applicable local, state, and federal laws. I assume no liability and is not responsible for any misuse or damage caused by this keylogger.
