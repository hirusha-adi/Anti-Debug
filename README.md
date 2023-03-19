# Anti-Debug

Detect Debug Mode and Sandboxes with C++

- built with,

```
> g++ --version
g++.exe (MinGW.org GCC-6.3.0-1) 6.3.0
```

# Approach

- ## Username Check

the evirement variable `USERNAME` is checked against a list

- ## HWID Check

the current system's HardWare ID is check against a list

- ## Computer Name Check

the current system's name is check against a list

- ## Path Check

these paths have been found in many sandboxing tools

- `D:\\Tools`
- `D:\\OS2`
- `D:\\NT3X`

- ## Path Check

check the mac addresses of the current system

- ## DLL Check

check for DLLs that are only found in Virtual Machines, this tools supports both VM Ware Detection and Virtual Box Detection

- ## Hardware Check

suspicous amounts of cpu cores and system memmory is also checked
