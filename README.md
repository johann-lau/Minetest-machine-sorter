# Minetest-machine-sorter

### Usage
This file sorts Minetest tools so that they can be sorted to the Tool Workshop or Battery Box.
Example:
Tool Workshop|Battery box
-|-
Multitools|Farm Machines
Pickaxes|Mining Drills
Staffs|Mining Lasers
Gliders|Prospectors

### Setup guide
1. Copy the whole code from the [raw file](https://raw.githubusercontent.com/johann-lau/Minetest-machine-sorter/main/Sorter).
2. Join Tunnelers' Abyss Minetest server.
3. Place a lua controller tube and connect it to the input chest, the battery box and the tool workshop.
4. Adjust the colours next to  `return` (on line 51 and 72) so that they direct to the right machines.
5. You are all set! Now you can sort the tools automatically.

### Troubleshooting
Problem|Reason|Solution
-|-|-
The tools don't go in the machines.|The machines doesn't have the required upgrade.|Put an advanced logic control unit in the upgrade slots of the machine.
Some tools are dropped.|The tool can't be identified.|Contact @johann-lau so that he can add the required tool.
"Machine has no network" appears.|The machine is not connected to an LV/HV network.|Make sure there is stable and enough energy supply. Also, check if you accidentally removed LV/HV cables. If you don't want to build new energy supplies, put a battery box in the upgrade slots of the machines.

### Notes from myself
This project is still under developement. Therefore, some tools might not be added. Thank you for your patience!
