[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 3

## Topics covered
(No date 😭)
* Turing machine
* Classic Von-Neuman architecture

30/09/2025
* How to use a rasberry pie

## Personal Notes
* A turing machine is a programmable, "turing complete", machine that can simulate calculations and program itslelf to adapt accordingly
* The "random access" in RAM is because it needs to be able to quickly take in data from anywhere
* ROM is "Read only" because thats all you can do: Read, not write. However this technically classifies as a type of RAM, just one you can't edit or write to
<img width="1999" height="1545" alt="image" src="https://github.com/user-attachments/assets/1f1442c5-2271-4d9b-aa8a-d75b88974d58" />

### Types of memory:
#### On cpu (in order of speed)
* Refisters
* Arithmetic logic unit
* Layer 1 cache
* Layer 2 cashe
* Memory management unit
* Swap file (?)

#### Off Cpu
* Static RAM (Very Expensive)/ Dynamic RAM (constantly leaks)
* External disk: Hard Disk Drive (Larger) / Soft Disk Drive (Faster)
* Removable: Floppy, SD card, Tape
* Virtual memory (?)

## Research
### Buses
* The things that transfer data from component to component, of which there are 3.
*  A bus is a collection of parallel physical conductors within von neuman archetecture that acts as a shared pathway between the CPU, main memory and input/output components, transfering different types of information: Data (the information), Addresses (the location of the data) and control signals (commands for the operation).
*  The **Data Bus** Carries actual data and instructions. It brings instructions from the memory to the CPU for processing and then carries the results back to the mamory (2-way). The actual "width" of the data bus (32-bit, 64-bit)  determines how much data can be transferred in one go, which tends to be a big factor in a computer's performance.
*  The **Address Bus** Carries the memory addresses. Goes straight from the CPU to the memory (1-way) whenever the CPU needs to read/write data. It places a specific memory address to tell the rest of the system where the data should come from or go to. The width Determines how much memory the CPU can access (32-bit = 4GB of RAM)
*  The **Control Bus** carries control and timing signals (the what and when): A collection of signals that coordinate the system's activities (2 way) through commands such as: Memory Read, Memory Write, Interrupt Request, Clock signal (syncronizes all operation).
<img width="876" height="302" alt="image" src="https://github.com/user-attachments/assets/a4474c39-25a7-4fce-baf4-34223926fe57" />

### Program counter
* Stores the address of the next instruction

## Exercises and results

#### Computer components
* Green = Ram
* Red = Power Source
* Yellow = Central Processing Unit
<img width="768" height="628" alt="Screenshot 2025-09-29 102445" src="https://github.com/user-attachments/assets/e6d9425e-140c-4016-b042-e98b1f0dcff5" />
<img width="1500" height="867" alt="Screenshot 2025-09-29 102124" src="https://github.com/user-attachments/assets/8db72dcd-bcd1-42d9-b4de-10c8e87cabe4" />

#### Rasberry Pi setup
* Shaun and I (mainly shaun) got the rasberry pi working

#### Node RED traffic lights
* Right, future me, I know this is gonna be hard to follow but I'll do my best to explain this absolute clusterfuck.
* This "System" is made to imitate how traffic lights actually work. 2 pairs of functions for each side of the street (one for switching on, one for switching off). The reason why there's two is because you don't want the cars to collide (?) don't want the timings to overlap (?) I really don't know 😭
* What I do know is that we needed 2 breadboards for this, one for each traffic lights, connected to different sets of GPIO (general purpose input/output) pins on the same rasberry pi (had to open it up for that)
* I did at some point fuck up the breadboard that shaun put together by putting the wrong wire into the wrong pin but its fiiiiine
<img width="4000" height="3000" alt="image" src="https://github.com/user-attachments/assets/3d77bdca-9c79-4807-8e3a-8dc535a8840b" />

* [Video of the the thing working](https://cdn.discordapp.com/attachments/1379408965342990436/1431235333319823563/VID_20251021_120235.mp4?ex=68fcad46&is=68fb5bc6&hm=68f9f8a7c0f92728865dd60bcc7544fe15b50bdaf04ee3fdcc32d9d1b2a2d3c1&)
* This was a nightmare, but its done now 👍



## Summary of learning
* Computers are a bit more complicated than I thought they would be, but still within reason so I'm not too concerned (foreshadowing)
* I now can set up a rasberry pi, but I'm not too sure about actually using one
* I can now use a rasberry pi
