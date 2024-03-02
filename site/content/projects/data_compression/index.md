+++
image = "compression.png"
date = "2023-09-01"
title = "LZ77 Optimization and Testing"
type = "gallery"
tags = "Data Compression, Testing"
+++

We optimized the LZ77 implementation on SCL. LZ77 is the basis for some of the most widely used compressors (gzip, zstd), but the current implementation on SCL does not use repcodes and uses Huffman coding for entropy coding. We believe with the addition of a basic repcode and by changing the entropy coding to rANS, tANS, or Arithmetic coding we will see an improved data compression rate. The following variations of the LZ77 compressor will be implemented: original SCL implementation, variation with rANS coding, variation with tANS coding, variation with Arithmetic coding, variation with repcodes, variation with repcodes and rANS coding, variation with repcodes and tANS coding, and variation with repcodes and Arithmetic coding.  These variations will be tested on different datasets (text file, random ASCII, and Github user information) to see which variation performs the best for each dataset. 

I worked as a part of a 2-person team to complete this project.

 [(Full Paper)](https://navinavi.notion.site/LZ77-Optimization-and-Testing-823bd4705f674ebbad125f093c7d42de?pvs=74)
