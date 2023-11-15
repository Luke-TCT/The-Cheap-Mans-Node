# The Cheap Man's Node
The world most accessible Bitcoin Node

A sleak Bitcoin node built by the plebs, for the plebs.

- Powered by the Raspberry Pi 4, the most widespread device for self-made nodes
- GeekPi Aluminum Case, to maintain the CPU and other important components at safe temperature
- UPS with 2x18650 Li-Ion batteries, to maintain the device operational, even when your electric grid is not
- Interlocking assembly/disassembly system, no screws required.
- OS Agnostic. You are free to run your preferred OS
- Cheap AF, designed to be reliable without wasting precious sats on expensive hardware
- Low Profile: Its rather limited dimensions (100x80x50 mm) allow you to place it, or hide it, anywhere you want
- Completely FOSS: buy one or 3D print the case and build your own

This FOSS project aims to create the world cheapest AND most reliable Bitcoin Node to lower the technical and economical barrier and reach true hyperbitcoinization.

Built around the Raspberry Pi 4, the most widespread device for self-made nodes, it significantly improve its reliability by addressing its downside in the most effective, yet economical, way possible.

Yours is the choice to buy a pre-assembled version of it (Pi4 and SSD NOT INCLUDED), or going the Cyperpunk way and making your own by downloading the 3D design of it for free and 3D Print it, purchasing the necessary components from your favoured distribution channel and assebling it. (note: unfortunately, some tiny bits of soldering is required)


FAQ:

- What is included?

It includes: all the 3D Printed components, 2x18650 Batteries, a 5V UPS board, a tiny voltmeter with a button to activate it, a USB-F soldered on the UPS, the GeekPi Aluminium Case (NO-fan) and the Sabrent SSD-to-USB adapter. The only components not presents are the Raspberry Pi 4 and the SSD


- Why the Raspberry?

Besides being cheap, It have some advantage compared to other alternatives.
Unlike common laptops, it consumes very little energy, saving you hundreds of thousands of sats every year on your energy bill.
Also, being one of the most common hardware used for Bitcoin nodes, it has plenty of guides and huge communities to support you in case of need.


- But Doesn't it have some reliability issue?

Yes, and No.
There are quite some misconception surrounding the reliability of the Raspberry's for this kind of use, so let's address them.
Being one of the most common hardware used for Bitcoin Node, it's quite natural that the most common problems discussed online are about them, but let's step away from this bias.
The most common and widespread issue involving them have, ironically, nothing to do with the hardware itself, and can be of three type:
1. Disk failures - They are unfortunately very common for RPi based node due to the widespread usage of microSD as the main location for the OS.
This is a BAD Idea. Do not run your OS on the microSD, it's just a matter of time before it fails. MicroSDs are not made for this kind of usage and the common reccomendation of using "rugged" ones will just delay the inevitable.
From what I've personally gathered, this represent over 90% of the serious non-reversible issues faced by the Bitcoin community, to which I can only reccomend you to not run your OS on them.
2. Overheating - The remaining hardware issues often involves the Ram being damage from overheating, which is due to the cooling system either being mounted only on the CPU, or being mounted but not correctly touching, and therefore not dissipating heat, of the Ram itself.
By using a good case that effectively cools down the main Raspberry Pi hardware, such issue would be significantly more rare to encounter.
3. Power outage - Sudden and Unexpected power outage or power spike can permanently damage the Raspberry and/or the content being written on the disk, forcing you to redo everything from skratch, once again. The usage of the UPS will guarantee you not only an impeccable uptime but also avoid the consequence of this issue.


- Can I use the UPS for other stuff?

Sure, the UPS is rated to constantly output up to 5A at 5 Volt, so you can connect to the USB other devices along the Raspberry, like a low power Router, to ensure you are always connected even during power outage.


 

