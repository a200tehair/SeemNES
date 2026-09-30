# SeemNES
NES emulator coded with LuaJIT & Raylib

This is unfinished and will probably be absolutely nothing but a license and this README for a while, I suppose you can take the time to read this other stuff though

This is a full command line project, so here's how you actually use this emulator

To start up the emulator, go ahead and execute these commands depending on your platform  
For Unix-like OSes:  
<code> ./raylua control.lua </code>  
For Windows:  
<code> raylua.exe control.lua </code>

To boot up a cartridge, simply type in any file containing 6502 assembly, then hit enter (once you've booted up the Lua runtime)

# What this supports
Being accurate enough to normal hardware  
Outputting disassemblies  
I didn't have much else to say here honestly  

# What this DOES NOT support
TASing (yet)  
Famicom Disk System (probably forever)  
100% Hardware Accuracy  
Most of the 'unofficial' opcodes (currently only the stable ones are supported)  
