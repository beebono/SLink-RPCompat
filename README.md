# SLink-RPCompat

A simple wrapper library implementation that intercepts incompatible DMA_HEAP calls and
reroutes them to the GPU of the Retroid Pocket 5/Mini

Built using "aarch64-linux-gnu-gcc -fPIC -shared -o librpcompat.so rpcompat.c"
