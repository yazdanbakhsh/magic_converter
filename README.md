This script provides a flexible yet comprehensive way to convert decimal "floating" point numbers to binary "fixed" point numbers and vice versa.
The current version(v1.0) only support the conversion between decimal and binary. Other bases will be added soon!
There is two possible way to call this script:

	1) converter [b2d|d2b] [number of bits] [number of fractions] [binary value | decimal value]

		- [b2d]: 					binary to decimal conversion
		- [d2b]: 					decimal to binary conversion
		- [number of bits]:			total number of bits in the presentation (including sign bit)
		- [number of fractions]:	number of fraction bits in the presentation
		- [binary value]:			the binary value to be converted to decimal
		- [decimal value]:			the decimal valye to be converted to binary

	2) converter -f [input file] -o [output file]

		- [input file]:				input file contains the commands to be executed by this script (take a look into the example folder)
		- [output file]: 			output file which all the results will be stored into (take a look into the example folder)

