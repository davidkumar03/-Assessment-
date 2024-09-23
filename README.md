Problem Statement :
You have a Heap of Size 128KB. Minimum Block Size to be given out is 1 KB. Design a Malloc and Free API to give and take memory back into the heap. Keep the following constraints :
Return Pointer to the memory
No memory can be given out twice consecutively
No memory can be freed Twice consecutively
Find the Best Fit for the memory SIze that is asked to reduce the memory wastage.
Example Calls :
            malloc( sizeof(int) * 128 ) ; // Should give a 1KB Block
            malloc ( sizeof(uint8_t) *1000 ) ; //Should give a 1 KB Block
            malloc ( 128*8*1024); //Should give 128KB whole block  
            free(ptr)
