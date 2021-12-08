# virtual-memory-

Consider a memory architecture using two - level paging for address translation .  The format of the virtual address , physical address , and PTE ( page table entry ) are below:

    

we calculated the bits needed as 2^48/2^12 which equals 2^36. after transferring the page size from 4kb into 2^2×2^10 =2^12, and representing the 48 bit as a power of two as follows 2^48. 

then for finding the number of entries we divided number of bits for the virtual address, over number of page sizs 

where, and why we come up with 16×1024×1024 which can also be written as 2^4×2^10×2^10, when we wanted to dedicate every entry for page?
