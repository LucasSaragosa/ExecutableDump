# ExecutableDump
Small program to dump all (null terminated) strings inside an executable for windows (or any file.)

### How to use this program

Simply start the program using the command line arguments explained below, or don't use any and write them in when the program starts.

##### Usage: exedump.exe -i "input file" -o "output file" [-v / -crc / -r] 

Use the -v option to be verbose</br>
Use the -crc option to dump the CRCs of the lowercase strings along with the dumped strings in the output file</br>
Use the -r option to enable experimental dumping of only the RTTI decorated class and struct names. (Uses dbghelp.dll, but if not available attempts without)
