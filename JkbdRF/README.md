Precondition for this to be of any use is a Tagsys RFID Reader for Library Stock. Either L-P101 or Medio P200x will do.
Both USB serial and TCP connections are supported.
Windows users will need proprietary device drivers,
Linux ans OSX just recognize the USB device as serial port and will be found. 

There is a simple trigger mode which allows for integration with web applications. 
Currently we use it together with Opensource Selfcheck, currently still at google code: 
https://code.google.com/p/open-source-self-check/

Once activated, the Java Program acts like a barcode reader.
Each medium will be read according to the "danish data model" and the "Barcode" will appear as keyboard input.
Media in reach are represented in a list and may be de/secured on demand.

The allowed barcodes may be filtered by a regex given in the rfid.conf file which is read as Java Properties.
