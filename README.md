# konami-code
This repo implements the eponymous Konami Code (UU-DD-L-R-L-R-B-A) using a circular queue. It is written in 6502 assembler and was assembled using *asm6* and tested with *fceux*. The source is well-commented.

The bash script *kc.sh* will assemble the source provided you have NASM (or another compatible assembler if you want to modify the script). The file *mario.chr* contains the sprite data for Super Mario Bros., which isn't used, but is necessary for the assembled file to load.
