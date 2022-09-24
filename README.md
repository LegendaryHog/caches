# My LFU and Belady caches on C++
**1. Cmake build**
```
cmake -B build/
cd build/
make
```

**2. Compare with other cache.**
```
chmod "+x" cmp
./cmp -b [EXE_OF_BELADY] -o [EXE_OF_OTHER_CACHE] [FILE_TEST1] ...
```
