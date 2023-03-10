# Nordos
Normalized Data Storage System
NOR Data stOr Sys
This project represent the technology of Adaptive Object Storage Environment.
AOSE system is aimed for achieving such characterisitis as:
- discovering all the unused space and bringing it for usage of blocks-wise file systems like NTFS, Ext2/3/4 & etc.
  The point is to utilize the space that is is left as unused in evey single block after putting the data into it.
  The the result is unfragmented space with data, increasing usage ration by 30% on common size files.
- do not involve defragmentation for utilizing unused space
- variable, adaptible block size
- simple, stright way of accessing objects metadata and data
- no performace compromises, io performance as the same as to file object access
- native compression with help of adaptive defragmentation in runtime
- no decompression naither special wat of metadata decoding. Possibility to open file object right in the data file.
- hierarchy of any depths and size.
- objects of any size
- possibility to keep any number of objects. Sclalbility on demand without restructuring
- Possibility to compute/calculate storage size with know data set. Predictable scaling.
