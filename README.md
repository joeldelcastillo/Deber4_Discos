### CMP-3004

### Computer Organization

### Spring 2022

# Homework 4

## Internal SSD
_Specs_

    - Processor: Ryzen 7 Series 400 Octa-core
    - Ram: 16 GB DDR4
    - GPU: RTX 2060 
    - Storage: M.2 SSD of 1 TB
     We used the distribution ubuntu 20.06 of Linux in a virtual machine called Virtual Box.  The commands we used were dd if=/dev/zero of=Escritorio/cmp3004/deber4/testfile.txt bs=256b count=1 oflag= direct,  and we tested for different values of bs which were 256b, 4k, 16k, 256k, 1M, and finally 1G.  Also we test with oflag=direct and oflag=dsync. 


_Commands_



256b:
![Flash](./Images/SSD/256bSSD.png)
4k:
![Flash](./Images/SSD/4kSSD.png)
16k:
![Flash](./Images/SSD/16kSSD.png)
256k:
![Flash](./Images/SSD/256kSSD.png)
1M:
![Flash](./Images/SSD/1MSSD.png)
1G:
![Flash](./Images/SSD/1GSSD.png)

_Graph_  
We registered the following results:  
![Graph](./Images/SSD/tableSSD.png)
![Graph](./Images/SSD/graphSSD.png)
## Internal HDD

## External HDD

_Specs_

    - Removable flash drive
    - Capacity: 32GB

_Commands_

256b:
![Flash](./Images/Flash/256b.jpeg)
4096b:
![Flash](./Images/Flash/4096b.jpeg)
16k:
![Flash](./Images/Flash/16k.jpeg)
256k:
![Flash](./Images/Flash/256k.jpeg)
1M:
![Flash](./Images/Flash/1M.jpeg)
256M:
![Flash](./Images/Flash/256M.jpg)
1G:
![Flash](./Images/Flash/1G.jpg)

_Graph_
![Graph](./Images/Flash/Picture1.png)

## Conclusions

    - What do you observe?
    - What are the main differences between the three drives?
    - What are the differences in performance when we change the value of `bs`?

- Why we see differences in performance for different values of `bs`?
- Try your experiments with `oflag=direct` and without it.
  - How do we explain the difference in performance of these two options?
