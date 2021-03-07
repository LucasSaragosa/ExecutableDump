# ExecutableDump
Small program to dump all (null terminated) strings inside an executable for windows (or any file.)

### How to use this program

Simply start the program using the command line arguments explained below, or don't use any and write them in when the program starts.

##### Usage: exedump.exe -i "input file" -o "output file" [-v / -crc / -r] 

-c : Flag to dump the CRCs with it (lowercased version)</br>
-v : Flag to be verbose</br>
-r : Dump only the classes and structs (RTTI deciphers), experimental!</br>
-i <input file> : Specify the input file (max 200 characters)</br>
-o <output file> : Specify the output file (max 200 characters)</br>
-a : Only dump alpha numerical strings</br>
