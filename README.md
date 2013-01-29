ecpyModule
=========

The ASE encrypt module of Traumx

编译so动态库：

gcc -shared -fpic -o ecpyModule.so eM.c -lm

#include "eM.h"

gcc xxxx.c -o yyyy ./ecpyModule.so
