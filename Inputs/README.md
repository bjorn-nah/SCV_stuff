# Inputs
Inputs atempt for Epoch / Yeno Super Cassette Vision.

Learnings about Inputs.
Use l7801 for compilation (https://github.com/BlockoS/l65)

Parts of the code was stolen from David Viens Plogue tester.

# Notes
The imput system is similar to c64 ones : you have to fill port A with voltage to chose the line to "call" in the input matrix and read port B to have the key pressed on it.

# Input matrix

| | Bit #7 | Bit #6 | Bit #5 | Bit #4 | Bit #3 | Bit #2 | Bit #1 | Bit #0 |
| ---:| ------ | ------ | ------ | ------- | ------ | ------ | ------- | ------ |
| **$fe** |  |  | P2 B1 | P2 UP | P2 LEFT | P1 B1 | P1 UP | P1 LEFT |
| **$fd** |  |  | P2 B2 | P2 RIGHT | P2 DOWN | P1 B2 | P1 RIGHT | P1 DOWN |
| **$fb** | #1 | #0 |  |  |  |  |  |  |
| **$f7** | #3 | #2 |  |  |  |  |  |  |
| **$ef** | #5 | #4 |  |  |  |  |  |  |
| **$df** | #7 | #6 |  |  |  |  |  |  |
| **$bf** | #9 | #8 |  |  |  |  |  |  |
| **$7f** | #EN | #CL |  |  |  |  |  |  |