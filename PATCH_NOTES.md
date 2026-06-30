# MQ2BardSwap Patch Notes

## FlopEQ Test Build - 2026-06-30

### Stability & Safety
* Made excluded song list handling safer.
* Made command string copying safer.
* Added character/spawn guards during pulse handling.
* Prevented empty or disabled swap commands from firing.
* Cleared command buffers when a swap entry is disabled.
* Made list entry creation safer.

### Build & Packaging
* Added build wiring for the current local MQ source tree.
* Verified Release x64 build and deployed the test DLL to the test MacroQuest plugins folder.

