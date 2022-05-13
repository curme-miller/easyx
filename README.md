# easyx
head files:graphics.h easyx.h
library:libEasyX.a


1.download TMD-GCC
2.put headers into TDM-gcc\x86_64-w64-mingw32\include
3.put library into TDM-gcc\x86_64-w64-mingw32\lib
4.command line:
g++ -g mai.cpp -I TDM-gcc\x86_64-w64-mingw32\include -LTDM-gcc\x86_64-w64-mingw32\lib -lEasyX -lole32 -lgdi32 -o main.exe
5.finish