# Image-converter-for-Dimatix
This program converts a vector image file to .ptn to be read by Dimatix Pattern Editor. For drawing software, [Inkscape](https://inkscape.org/en/) is highly recommended.

### Requirement ###
#### Python version ####
+ Python 2.x

### Usage ###
#### Python version ####
Run the program with input file as system argument(s).  
You will get the output as ``example_[layername].ptn``.  
    ``python converttoDimatix.py example.svg``
#### Windows version ####
Drag & drop your vector file to ``.exe``.  
If you cannot drop a file and if you have your vector file and ``.exe`` in the same folder, try copying the ``.exe`` to other place (i.e. Desktop) then drag & drop the vector file. A ``.ptn`` appears in the same directory as your vector file.

### Tips for vector image designing ###
Make sure to set **unit** of the draw software to **mm**, otherwise you will get a converted image in a different scale.

### Supported format ###
**Rectangler elements only!**  
+ .svg by Inkscape

-----
# Updates
2017 Nov 15 Version 1.15 Variable jet spacing by argument  
2017 Mar 17 Version 1.14 Now compatible with rotated rectangles (negative coordinates) and minor bug fixes  
2015 Dec 09 Version 1.11 Minor bug fixes  
2015 Dec 09 Version 1.10 Multi-layered .svg can now be converted. Each layer will be named as [filename]_[layername].ptn  
2015 Dec 07 Version 1.01 Scaling problem solved  
2015 Dec 03 Version 1.00 Windows drag & drop executable avilable!  
2015 Dec 02 Version 1.00
