# ProcList
C++ Script to list active processes with name, PID, Parent ID and User running it

# Compile

![image](https://user-images.githubusercontent.com/79543461/218267621-ec95c0c4-958b-4303-8fe0-22994ec58709.png)

Command:
x86_64-w64-mingw32-g++ -O2 ProcList.cpp -o procList.exe -I/usr/share/mingw-w64/include/ -s -ffunction-sections -fdata-sections -Wno-write-strings -fno-exceptions -fmerge-all-constants -static-libstdc++ -static-libgcc -fpermissive
