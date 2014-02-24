Project: Monitor Project (CISC OS)
Author: Jeff Grindel 
File: MONITOR.X68
___________________________________________________________________________________________
Description: A program used as a debugger/monitoring program for the MC68000 microprocessor. 
It is written using CISC on the MC68K instruction set in mind, however this specific program 
was written with the Easy68K software for easier debugging purposes and because the MC68K processor
was not always available to work with when this was written. Thus will only work within the Easy68K 
simulation software since it has its own specific set of TRAP functions that differ from the 
ones specified in the MC68K instruction set. Download link to Easy68K below. 

Software needed:  http://www.easy68k.com/

Setup: To run this file download the .X68 file, this is the source file for Easy68K. Once loaded
in the simulation program Assemble Source(F9 Shortcut). Given that the program was not modified 
there should be no errors, hit the execute button when the prompt comes up. The specific program 
starts at the PC value 0x19D4. If the simulation software does not automatically set this manually 
set the PC value. When you run the program a prompt with display with MONITOR>, you can now start 
entering in the commands. Further documentation can be found in the Project_Report.pdf.

Also see http://jeffgrindel.com/CISC_OS.html
