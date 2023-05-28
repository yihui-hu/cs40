# CS40 Machine Structure and Assembly Language Programming

This repository[^1] contains projects from Tufts University's [CS40](https://www.cs.tufts.edu/comp/40/) course, which I took in Fall of 2022. 

A brief overview of the projects:
1. ```filesofpix``` is an image restoration program and our first introduction to [Hanson data structures](http://www.r-5.org/files/books/computers/languages/c/mod/David_R_Hanson-C_Interfaces_and_Implementations-EN.pdf)
2. ```iii``` comprises two parts: a Sudoku solutions validator and a tool that unblacks edges of an image, like a scanned document
3. ```locality``` is an image rotator/flipper optimized using [the principle of locality](https://en.wikipedia.org/wiki/Locality_of_reference)
4. ```arith```[^2] is an image (de)compressor utilizing quantization and bitpacking
5. ```bomb``` requires an analysis of assembly-language programs to defuse 'binary bombs'
6. ```um``` is an implementation of a simple virtual machine called the “Universal Machine” (UM)
7. ```profiling``` is an aggressive optimization of the ```um```, achieved through stripping away multiple layers of abstractions
8. ```asmcoding``` is a calculator using [Reverse Polish notation](https://en.wikipedia.org/wiki/Reverse_Polish_notation) written in ```umasm``` (i.e. universal machine assembly language) and runs exclusively on the ```um```


[^1]: Because this repository contains university coursework, all project folders are symbolic links to private repositories containing their individual source code. If you'd like to see the actual source code, please contact me via yyihui.hu (at) gmail (dot) com.

[^2]: ```arith``` is also available as an online tool [here](https://arith.vercel.app)! Feel free to check it out. The source code for the frontend of the website is also available on [GitHub](https://github.com/yihui-hu/arith-js).