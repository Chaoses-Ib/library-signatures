# GMP
- String signatures

## mini-gmp
Export all functions:  
mini-gmp.h:
```regex
^(?!#)(?!typedef)(.+?) (mp[nz])
```
```regex
__declspec(dllexport) $1 $2
```