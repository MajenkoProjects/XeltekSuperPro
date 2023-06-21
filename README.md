Xeltek SuperPro ISA Card
========================

The original work credit has to go to Matthieu Benoit for his stirling work in reverse engineering and
developing the first version of the SuperPro ISA card.

This version builds on the original work and cleans it up a little, fixing a few bugs in that version.

The original can be found here: http://matthieu.benoit.free.fr/xeltek_superpro_programmer.htm

Originally the reverse engineering and design was created by Janusz Chałupnik (link pending - when I get details let's shower him with gratitude for his hard work)

Changes
-------

* The original PCB had two missing traces which have been added
* The original schematic had an OR gate missing for timing correction in the IOCHRDY pulse generator
* The separate ground traces have been replaced with full-board ground pours

This design has been created using `sch-rnd` and `pcb-rnd`.
