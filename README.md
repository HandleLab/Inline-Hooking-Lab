# Inline-Hooking-Lab

A personal learning project on x86 inline hooking, written in C++ as a 32-bit DLL.

It scans the game's memory with byte patterns and masks to locate key data structures (local player, entity list), then installs an inline hook (detour with trampoline) on the game's shooting function to redirect its target.

Built on an old version of AssaultCube, in single-player against bots, purely as a learning exercise. Not intended for online use.
