# Mac Plus PS/2 Mouse Adapter

This is a simple small adapter that transforms your PS/2 mouse into a proper
Mac Plus mouse.

Much thanks to Andreas for this code to work from.  I only had to tweak a few
things here and there.


# Hardware
All you need is:
- a microcontroller running on +5 VDC with 10 digital I/O pins. I'm using
  an Arduino Pro Mini clone with an Atmel ATmega168 (5V, 16 MHz)
- a female DE-9 (D-sub 9) connector
- a female PS/2 connector
- a soldering iron

# Setup
1) Connect the female DE-9 connector to the microcontroller. See the "Output pins"
   definitions in the code.
2) Connect the female PS/2 connector to the microcontroller. See the "Input pins"
   definitions in the code.
3) Compile and upload the sketch.

# Usage
Just plug the adapter between your Mac Plus and your PS/2 mouse. 

# Logic Analyzer files
You can use Saleae's Logic 1.2.18 (available at https://www.saleae.com/downloads/) 
to view the files in `logic_analyzer_data`.
