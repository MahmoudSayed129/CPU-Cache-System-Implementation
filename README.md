# CPU Cache System Implementation

This project presents a simplified CPU cache system implementation in Prolog and Haskell. The cache system is designed to store and retrieve data efficiently, reducing access time by temporarily storing frequently used data.

## Project Description

### Memory Hierarchy
The cache system introduces hierarchy into memory systems by utilizing multiple levels of caching. The project assumes two levels of cache as depicted in Figure 1.

### Cache Operation
1. A specific block of data is requested, identified by its location in main memory.
2. The system checks if the block is mapped in the cache.
3. If found in cache, the data is retrieved from cache.
4. If not found in cache, the block is fetched from main memory and placed in cache.

### Cache Mapping Types
Three cache mapping techniques are implemented:
- Direct mapping
- Fully associative mapping
- Set associative mapping

### Address
Memory addresses are split into index and tag fields. The index indicates the cache location, while the tag identifies the block.

### Cache Options
The number of options in the cache determines the number of bits needed for the index part.

## Implementation Details

### Prolog Implementation
The Prolog implementation includes components for direct mapping, set associative mapping, and block replacement.

### Haskell Implementation
The Haskell implementation mirrors the Prolog implementation, providing functionality for cache operations and block replacement.

## Requirements
- Prolog and Haskell implementations for the cache system.
- Division of specific components among team members:
  - Direct mapping
  - Set associative mapping
  - Block replacement (optional: fully associative mapping)

Feel free to explore and modify the code to experiment with different cache configurations and replacement strategies.

---

This project is implemented in Prolog and Haskell to demonstrate the versatility and flexibility of different programming paradigms in solving computational problems.

