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
- Possibility to use over network as extandable Network Object Storage.

Usage

1. Archive storage. Space saving multi-trillions object storages.
2. Designed to be true back-end for such techs like Hadoop HDFS, or data warehouses, 
3. Instant access to objects easy resolving problem with huge number of small files on the host. 
4. It reduces power consumption and, consequently, electricity costs in comparison with Hadoop FS and other Java-based solutions at 50% according this paper, decreasing the TCO (Cost Of Ownership). It can outperform Hadoop FS greatly while tackling tasks with multimillion datasets.
5. File system for small single board computers. Hence Nordos is adaptive highly-configurable object storage, it can save a lot of space on their drives.
6. Normalized Object Storage Environemnt
Adaptive Object storage chain
Adaptive Object storage system
Adaptive Object Chain
Adaptive Normalized Object Chain
Adaptive Object Chain


The public article 
https://medium.com/@focused_tuscan_bee_454/ntfs-hunting-for-30-unused-disk-space-with-nordos-tech-b7f5a577ef3c
with practical value.


Try Projects
https://www.wevolver.com/article/the-rock-engineering-challenge?li_fat_id=fa85e3f5-11d8-496a-90d2-ba07916739bc


