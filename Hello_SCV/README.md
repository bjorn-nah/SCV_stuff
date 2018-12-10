# Hello World SCV
Hello world for Epoch / Yeno Super Cassette Vision.

Based on Enri's one (http://www43.tok2.com/home/cmpslv/Scv/EnrSct.htm)
Personal attempt to create a svc rom without compiler.
All assembly mnemonics are manualy converted to opcodes and reported in
an hexadecimal editor.

Hello_SVC_src.txt is the source structured in 3 columns: asm / opcode / comments
Hello_SVC.bin is the rom image

VDC_DATA are located at $0020 (cartrige port is $8000, so data are loaded at $8020)
MS_DATA are located at $0030 and are 0F long. (16 caracters)