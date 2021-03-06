# LC-Filter-PCBs
LC filter board PCB designs.

Allows for a wide variety of LC filters (up to 5-pole) to be rapidly prototyped.  

Capacitor pads are 0805, but 0603 and 1208 will fit if hand-soldering.  Pads are doubled up to allow fine-tuning by adding a second, smaller capacitor.  Use of low ESR/ESL C0G type recommended.

Inductors pads are custom pads that allow any of the following to be installed from convenient Coilcraft deigner kits:  
[Coilcraft 1812LS](https://www.coilcraft.com/1812ls.cfm) - Ferrite core chip inductors 12-1000uH  
[Coilcraft 1812CS](https://www.coilcraft.com/1812cs.cfm) - Ceramic core chip inductors 1-33uH  
[Coilcraft 1515SQ, 2222Q, 2929Q](https://www.coilcraft.com/1515sq.cfm) - Air core inductors 47-500nH  

Filters can be designed using the [iFilter](https://www.awr.com/software/options/ifilter) feature of [AWR Design Environment](https://www.awr.com/software/products/awr-design-environment), for which free educational licenses are available.  [Elsie](http://tonnesoftware.com/elsie.html) is a simpler, but somewhat outdated, alternative.

Boards designed using Altium Designer 19.  Pdf files can be found in [releases](https://github.com/OregonIons/LC-Filter-PCBs/releases).

An enclosure design is forthcoming.  In the mean time, edge mount SMAs can be used for testing.
