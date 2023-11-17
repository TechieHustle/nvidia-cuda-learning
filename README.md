# nvidia-cuda-learning
I learn and document my findings related to CUDA programming to this repository.

### Parallelizing in CUDA:
- Threads are organized in groups called "**thread blocks**" and thread blocks are organized into grids.
- A grid with M thread blocks and T threads in each thread block is specified using `<<< M , T >>>`.
- 
