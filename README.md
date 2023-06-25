# hash-map

Simple implementation of hash map. Hashed keys are stored in an array of nodes, if different keys get the same hash value we add them as next node at given index. When the number of elements divided by size exceeds a maximum, size of the hash map is increased twice and all keys are rehashed
