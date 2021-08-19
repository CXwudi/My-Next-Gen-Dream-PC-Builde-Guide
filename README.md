# My Next-Gen Dream PC Build Guide

This is the detailed build guide for [my next-gen dream PC build](https://ca.pcpartpicker.com/user/CXwudi/saved/#view=MqFGGX)

## Caution

1. install every independent thing that can be installed on the motherboard
   1. CPU
   2. RAM (from most outside, plug into the 1 and 3 slots)
   3. M.2 SSD
2. CPU Cooler has a plastic label on the CPU touch side, remove it!
3. For AIO CPU Cooler, the highest point must not be the pump
   - the highest point is where the air gets trapped, air on the pump will make harsh sounds and break CPU Cooler
4. if going top-mount AIO CPU cooler, make sure the air is going outside from the case through the radiator, not going inside from the outside through the radiator
5. Make sure to watch out the fan blow direction
   - it usually goes from clean side to the side that has bones that holding the fan engine
   - some fans may have arrows pointing the direction
6. IF YOU LOSE A SCREW OR OTHER SMALL METAL OBJECT, DO NOT TURN ON YOU COMPUTER UNTIL YOU FIND IT

## Phase - before buide

### before the day of building

1. Read all manuals
2. Get ready for a safe clutter free anti-static workstation
3. Get these tools
![tools](./Screenshot%202021-08-11%20001202.png)
   - scruw driver
   - a part tray
   - knife
   - side cutter
   - needle nose pliers
   - thermal compound (or liquid metal)
   - cable ties
4. Setup and test the streaming environment
   - use phone. it may draw battery too fast, but it is potable.
5. Design the cable management
   - from PSU to all slots on MoBo, going through which way
   - you might need a paper and pen to do the design (or surface book 2)

### on the day of building

1. Clean the table, get all tools standby
2. surface book 2 standby, with all tutorial videos opened
   - specially need [this](https://www.youtube.com/watch?v=PXaLc9AYIcg) video
3. Recording things that needed for the vlog
   - An introduction in JP (used in intro)
   - all parts pictures/videos (used in PC parts introduction part)
4. Open Streaming

## Phase - during build

### on MoBO only

1. Make myself static-safe
   1. take out the power supply
   2. turn off the power supply
   3. connect it
   4. connect myself with a anti-static strap to the power supply
2. Carefully take out the MoBo and put it on top of the MoBo box
   - reason: box provide anti-static work surface
   - also, when taking out, not touching any component on top and back, for example:
![taking out Mobo](./Screenshot%202021-08-15%20180651.png)
![place on box](./Screenshot%202021-08-15%20180812.png)
3. Install CPU
   - lift up the MoBo lever
   - hold the CPU on the side
![hold CPU](./Screenshot%202021-08-15%20181129.png)
![CPU to Mobo](Screenshot%202021-08-15%20181225.png)
   - gentally place it on MoBo
   - watch out the arrow, arrow line up
   - no big forces, don't scruw up the CPU's pins, lift down the lever
4. Install RAMs
   - watch out the orientation, by looking at slots
   - RAMs on first and third slots starting from outside
   - RAM is successfully installed when you hear "click" on both sides of the RAM
5. Install SSDs
   - remove MoBo heat spreader, if it has one
   - watch out if the MoBo heat spreader has a cover like in the image
![sample heat spreader cover](./Screenshot%202021-08-15%20181707.png)
   - check my SSD length, install the female screw.
   - put the SSD
   - install the child screw on the mother screw 
   - install back the heat spreader

### installation on PC case

1. Take out the PC case
2. But put front, left side, right side panels back to the box
   - make sure put the bubble material between two panels to avoid scretching
3. Do cable pre-management
   - only for cables from the case, which cable go to where, so that when the MoBo is installed, all cables are standby
4. Lay down the PC case
5. (Skip if IO shield is integrated with MoBo) Validate and install the IO shield 
   - validate means IO shield fit the Mobo, fit the case, and shield doesn't block any port
6. Carefully put on the MoBo, and install it
   - 10% - 15% angle goes in
   - must be really careful of not letting the PC case scretches the MoBo
7. Lay up the PC case
8. (Skip if AIO Cooler comes with a build-in thermal paste && build-in thermal paste is not touched) Add thermal conpound to CPU
9.  Install AIO Cooler
   - must make sure not touching the thermal paste
   - front mount
   - make sure the most top point is not the pump
   - not the cable part yet
10. Install all fans
11. Do a little bit of lifting left, lifting right. to make sure bubbles in AIO Coolers goes up
12. Remove the PSU cover, unpack anti-static protection, and install PSU
    - make sure fans is facing downside so that fans can poll fresh air to PSU

### cable management on PC case

Notice: All cable management should be done just-in-time

1. plug in all cables on the MoBo side
   - usb 3.0, use 2.0
   - audios
   - usb c
2. AIO Cooler fans
   - goes to the AIO commander
3. AIO Cooler pump
   - thin one goes to AIO pump/CPU fan header
   - thick one goes to commander header
4. AIO Cooler commander
   - usb one goes to usb header in MoBo
   - thicker one goes to Sata female cable from PSU then Sata female cable goes to PSU
5. Other fans
   - goes to the fan hub integrated in the MoBo
6. Front Panel cables
   - follow the [video](https://youtu.be/PXaLc9AYIcg?t=2978) or the screenshot below
7. 24 pin MoBo cable
8. EPS (CPU) cable (both cable)
![front panel pins](Screenshot%202021-08-16%20180348.png)

### final installation

1. Install GPU and connect its wires
   - when connecting the PCIe cables, don't use these pigtails. Instead, use all 3 PCIe cables and leave these pigtails alone
2. Install GPU supporter
3. Install MoBo WiFi

## Phase - after build

### MoBo settings

1. Upgrade MoBo driver to support 5950x CPU
   - by this [tutorial](https://www.youtube.com/watch?v=OmxphAtiSl0)
2. Connect HDMI on GPU, mouse and keyboard
   - not the DisplayPort since NVIDIA driver hasn't installed yet
3. Boots up, immediately go to BOIS settings
4. In BIOS page, check all status
   - CPU
   - GPU
   - RAMs: make sure to enable XMP
   - SSDs: make sure to enable Fast Boot in the Boot section
   - temperature
   - noise
5. If anything is shown wrong in BIOS, debug and fix it before progressing to the next step.
6. Install back the front, two side panels, check noise again

### Windows/Drivers install

prerequisite: MoBo setting is correct, all hardware works properly

1. From BIOS, boot from the Win10 installation USB
2. Install Windows 10, login my microsoft account
3. Perform our own Win10 setting customization based on OneNote
   - no need to start installing app now, just changing win10 setting
4. put in the MoBo CD to install some drivers
5. At this stage, the PC is in usable status
6. Install chocolaty and [properly config it](https://stackoverflow.com/a/45019227/8529009) as it is needed for the next step

### Unit tests && Integration tests

prerequisite: the PC is in usable status

1. Run followings to check CPU and GPU are in good performance:
   - Cinebench r20
   - FurMark
2. Check followings to see all system spec are correct, including RAMs
   - CPUz
   - GPUz
3. Run CrstalDiskInfo to check both SSDs speed meet expectation
4. Play 30 minutes of Apex Legends with MSI Afterburner to check if normal game play is fine
   - this also check long time heavy load
   - observe if any abnormal high temperature or FPS drop happens
5. Stream 30 minutes of Apex Legends with MSI Afterburner and OBS to see if multi-tasking works well
   - should not expect a massive FPS drop compared to not streaming
6. Install Graalvm and Intellij (using JetBrain Toolbox), do some development on my personal project [`vocadb-video-downloader-new`](https://github.com/CXwudi/vocadb-video-downloader-new)
   - should run smoother

### Anything left?

prerequisite: all checks are done, PC is in production state

1. Just like how we setup Surface Book 2, setup everythings else based on notes in OneNote
2. Enjoy!
3. Watch out all faulty components. If anything happened, goes for RMA