# Brick-Odd-Even-Sort
### Parallel CUDA implementation of ODD-EVEN-SORT , a variant of bubble-sort



# Core Algorithm:
## Array of size n
1. Split the array into pairs and number them
2. Parallelly sorth the even pairs 
3. Parallelly sort the odd pairs
4. Repeat steps 3) and 4) n times 
