# Report
I used the hello.cpp file using a full cache, data cache, and instruction cache. <br>
Cache sizes: 1024, 2048, 4096, 8192, 16384 <br>
Associativity: Direct Mapped, 2-way, 4-way, and 8-way <br>
Replacement: LRU <br>

In a full cache with size 2048 and direct mapped associativity, the cost would be 2048. There is no extra cost from associativity. <br>
In a data cache with size 1024 and 2 way associativity, the cost is 1024 + 102.4 = 1126.4 <br>
In an instruction cache with size 1024 and 4 way associativity, the cost is 1024 + 204.8 = 1228.8 <br>
The combined cost of separate data and instruction caches is 2355.2 <br>
In this case, a full cache will be better than having separate data and instruction caches. <br>

# Graphs
Attached with the repo.