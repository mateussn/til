# GBA Memory Map

----  MEMORY AREA  ---- | ------------MEANING------------ | ----- LENGTH -------- | -- BUS -- |
                        
00000000 - 00003fff ---> BIOS(Basic Input/Output System) --> 16kb || 16383b --> 32bit

02000000 - 0203ffff ----> WRAM(Work Ram(On Board)) --> 256kb || 262144b --> 16 bit

03000000 - 03007fff ---> WRAM(Work Ram(On Chip)) ----> 32kb || 32768b -----> 32 bit

04000000 - 040003ff --> Input/Output Registers -------------> 1kb || 1023b --------> 32bit

05000000 - 050003ff --> Background/Object Palette Ram ---> 1kb || 1023b ------> 16bit

06000000 - 06017fff ---> VRAM(Video Ram) -----------------> 96kb|| 97518b ------> 16bit

07000000 - 070003ff --> OAM(Object Attribute Memory) --> 1kb||1023b ---------> 32bit 

08000000 - variable ---> Game Pak ROM ----------------> variable(max 32mb) ---> 16bit 


