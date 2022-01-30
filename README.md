# kagami
A simple sinatra server of GSI Maps Vector Tiles for UNVT Portable

![social preview image](https://repository-images.githubusercontent.com/445690045/0fcd3cef-90e5-4bac-a30c-c6ddc684a6df)

# Demo
1. Tiles are available at `https://x.optgeo.org/kagami/zxy/{z}/{x}/{y}.pbf`.
2. A demo site is at https://optgeo.github.io/nagi-names

# vt-optimizer output
```
pi@m354:/mnt/hdd $ node ~/vt-optimizer/index.js -m experimental_bvmap.mbtiles
No vector layers found
  ✔ Parsing VT file contents

Vector Tile Info
Zoom levels:  4,
Format:  pbf
Center:  135,27.88828650933385,10
Layers: 


Vector Tile Summary
Zoom level  Tiles    Total level size (KB)  Average tile size (KB)  Max tile size (KB)                                                                       
----------  -------  ---------------------  ----------------------  ------------------  -                                                                    
4           5        45.0537109375          9.0107421875            19.46484375         ✓                                                                    
5           11       56.646484375           5.1496803977272725      23.0927734375       ✓                                                                    
6           30       147.958984375          4.931966145833333       38.8740234375       ✓                                                                    
7           67       187.6181640625         2.800271105410448       21.0634765625       ✓                                                                    
8           391      4298.20703125          10.99285685741688       249.1396484375      ✓                                                                    
9           1296     7532.9306640625        5.8124465000482255      123.69140625        ✓                                                                    
10          4644     15032.5615234375       3.2369856854947243      86.1357421875       ✓                                                                    
11          6311     44464.1494140625       7.045499827929409       55.5673828125       ✓                                                                    
12          23627    67232.982421875        2.8455996284706058      27.3818359375       ✓                                                                    
13          90378    188030.900390625       2.0804941511277635      268.4765625         ✓                                                                    
14          138881   3685576.3779296875     26.53765726002612       299.2294921875      ✓                                                                    
15          544735   7026290.255859375      12.898547469612518      231.9287109375      ✓                                                                    
16          2157827  10059034.036132812     4.661649908047686       87.7646484375       ✓ 
```

# About the social preview image
The [social preview image](https://repository-images.githubusercontent.com/445690045/0fcd3cef-90e5-4bac-a30c-c6ddc684a6df) is from [Mirror With the Design of a Nine-Tailed Fox by Harukawa Goshichi](https://www.metmuseum.org/art/collection/search/55068).
