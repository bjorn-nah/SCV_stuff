# Sprite
Sprite atempt for Epoch / Yeno Super Cassette Vision.

Learnings about sprites creation.
Use l7801 for compilation (https://github.com/BlockoS/l65)

# Notes
SCV can display 128 sprites, but 64 first ones are "background" ones.
The backgrounds sprites are monochronic only (1 color + tranparancy), the last 64 ones can be multocolor (2 color + tranparancy I presume?)


Sprite data:
```
0000 0011 1100 0000		00 3F CF 00
0000 1111 1111 0000

0001 1111 1111 1000		13 FF FF 8C
0011 1111 1111 1100

0011 1111 1111 1100		37 FF FF CE
0111 1111 1111 1110

0111 1111 1111 1110		77 F3 F8 EE
0111 0011 1000 1110

0111 1001 0001 1110		73 99 11 EC
0011 1001 0001 1100

0011 1111 1111 1100		31 FE FF C8
0001 1110 1111 1000

0000 1111 1110 0000		01 FF EF 00
0001 1111 1111 0000

0001 1111 1111 0000		10 FA FA 00
0000 1010 1010 0000
```

# Todo
Test multocolor mode