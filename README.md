# Zork - The Pre-Infocom Classic
The aim of this project is to understand the design of Zork by means of re-engineering.

The objectives are as follows.
* Zork will be re-written in Inform 7 to represent it's design in a more easily understood, "natural-language" form.
* Gameplay of the Inform 7 version will be compared with that of the original to demonstrate fidelity of translation.
* Notes, maps and puzzle dependency graphs will be produced to document the design.

## Technical Context
Inform 7 v 10.1.0 has recently been made [open-source](https://intfiction.org/t/inform-7-v10-1-0-is-now-open-source/55674).
This presents an opportunity to use Inform 7 as implemented by the very latest version of the Inform compiler.
The specifics of this project are as follows.

### Languages
* [MDL](https://en.wikipedia.org/wiki/MDL_(programming_language))
* [Inform 7](https://en.wikipedia.org/wiki/Inform#Inform_7)

### Platforms
* Windows 10 / Cygwin

### Resources
* [Cygwin (latest)](https://www.cygwin.com/)
* [64-bit Windows Inform IDE beta (latest)](https://github.com/DavidKinder/Windows-Inform7)
* [Inform compiler version 10.1.0-beta 'Krypton' (latest)](https://github.com/ganelson/inform)
* [Mainframe Zork for Confusion](https://github.com/heasm66/mdlzork)

## Release Plan
The first release will implement the full map and will be navigable without solving puzzles. It will not implement puzzle solution logic, events or NPCs. No commands will be implemented other than those provided by the Inform library.

The content and number of further releases will be decided when necessary.
