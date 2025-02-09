CapSeg
======

CapSeg - Copy number from exome sequencing


Aaron McKenna <aaronmck at uw.edu>

CapSeg is a tool for transforming exome sequencing data to copy number information in cancer samples.  
Using a toolkit based on the GATK, Queue, R, and python, CapSeg transforms input paired tumor-normal
BAM files into segmented copy number calls.  

Prerequisites installed on the machine are:
  - Java 1.6.anything; Java 1.7 is not yet supported
  - Python 2.7+ (Python 3.X is not yet supported)
  - R 3.0 or greater, including the following packages:
      - optparse
      - DNAcopy
      - plyr
      - corpcor
  - Samtools (any version should do)


Versions
--------

*v1.0*
- Initial commit

*v1.0.1*
- Introduced seperate directories for input and output of the tangent planes (historical data)
- Minor bug fixes


