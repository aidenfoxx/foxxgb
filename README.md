# FoxxGB
FoxxGB is a simple Gameboy written in C designed to be highly portable. Display and input are abstracted so that they can be tied into various devices without altering the emulation core.

![FoxxGB Running Tetris](images/tetris.png)

### What's implemented?
- All CPU instructions
- Memory Management
- GPU timings with interrupts
- Timer with interrupts
- Input with interrupts
- Support for 32kb ROM only cartridges
- Background and basic sprite support

### What's not implemented?
- Sound
- Advanced sprite functionality (Palettes etc)
- Full sprite priority support
- Stat interrupts
- Full cartridge support (MBC 1,2,3 etc)

## How to use
To play a game simply drag the rom onto the executable.

# Requirements
FoxxGB requires the GLFW3 library to compile.

### Controls
Directions = Up, Down, Left, Right  
Start = Enter  
Select = Space  
B = Z  
A = X  
Close = Escape  

## Why make another Gameboy emulator?

*The short answer:* I was bored.

*The long answer:* I'd always wanted to make an emulator, but the task always seemed too much of a mountain to climb. I chose the Gameboy due to the obvious challenge, and excellent documentation surrounding the hardware. The choice was also motivated by CTurt's Gameboy emulator Cinoop (https://github.com/CTurt/Cinoop), the documentation for which helped me a number of times during development.

## Notes
The emulator is still very rough and has not been completely tested. The only game likely to work is Tetris.