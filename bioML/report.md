# SBML Solver Project

## Abstract


### Motivation 
This paper presents Systems Biology Markup Language (SBML) solver which is a extensible, high-performance, cross-platform, open-source software library. SBML is a shared library that loads, compiles and executes models written in the SBML language. The solver is designed to be included into other existing programs. The SBML solver fits into a suite of physics (fluids, soft-matter, visco-elastic) and computational biology called ‘Mechanica’. This module is designed to calculate the time evolution of a chemical network that’s attached to some simulated physical object (such as cell, membrane, volume), so forth.

   Building the SBML solver involves tracking down a lot of dependencies and it’s important for users who want to compile it to have clear instructions on how to do so. The SBML Solver will also be connected to integrate a PhysiCell software package. 


### Results 

Results

### Availability and Implementation 

The SBML solver is available to run on Mac OS X, Linux and Windows. 

## Introduction

Introduction 

## Methodology 

1. Worked to both document and improve software build process for SBML solver
2. which included better documentation process and determing missing steps
   1. Needed libxml2, zlib12 and libncurses.
  The project was initiated to both document and improve the software build process for the SBML solver. Which included a better documentation process and determining the missing features that were not in the build instructions. While documenting the build system I noticed there were a few missing features that were needed to run the SBML solver. For example,  I updated the build instructions to add and download libxml2, zlib12 and libncurses.
   2. Libxml2 is a free software that is a version of XML which is a metalanguage to design markup languages, i.e. text language where semantic and structure are added to the content using extra "markup" information enclosed between angle brackets[1]. The library is written in C but there are a variety of language bindings to make it available in multiple environments[1]. Libxml2 is effective due to is flexibitly to run on most operating systems such as Linux, Windows and MacOS X. 
   3. Zlib12 was created by Jean-loup Gailly and Mark Adler to be a free open source lossless data-compression library to be used on virtually any computer hardware and operating system[2]. It's compression method, an LZ77 variant called deflation, emits compressed data as a sequence of blocks[3]. Various block types are allowed, one of which is stored blocks—these are simply composed of the raw input data plus a few header bytes[3].
   3. Libncurses is a freely distributable library, fully compatible with older versions of curses[4]. It forms a wrapper over working with raw terminal codes, and provides highly flexible and efficient API (Application Programming Interface)[4]. It provides functions to move the cursor, create windows, produce colors, play with mouse etc[4]. The application programs need not worry about the underlying terminal capabilities [4].
3. downlaod required dependencies 
4. Compling and installing software

   
### Explain the uses of

1. Linux
      Open source software
      Distributions are different versions such as Ubuntu and Mint 
      Focuses on security and durability
   
2. Git
      Git is a distributed version-control system for tracking changes in source code during software development
      It is designed for coordinating work among programmers, but it can be used to track changes in any set of files
  
3. Ccmake
      
4. Cmake
      Cross-platform free and open-source software tool for managing the build process of software using a compiler-independent method. 
      Very useful with development of makefiles

 5. Gcc
      GNU Compiler Collection 
      An integrated distribution of compilers for several major programming languages
      C, C++ and Java
    
## Conclusion

The SBML Solver 

## Data

## Future Work

## Acknowledgements 
   REU, Indiana Univeristy, Andy and Georgey 

## Refernces 
 1. http://www.xmlsoft.org/
 2. https://zlib.net/
 3. https://zlib.net/zlib_tech.html
 4. https://www.tldp.org/HOWTO/NCURSES-Programming-HOWTO/intro.html

command time
makefiles
