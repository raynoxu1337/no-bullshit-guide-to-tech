# Assembly

Here you are kiddo. Assembly. It's basically human readable version of bytecode.

Which one do you prefer?

| x86 Assembly                                               | x86 Bytecode (Hex)            | x86 Bytecode (Binary)                                                                               |
| ---------------------------------------------------------- | ----------------------------- | --------------------------------------------------------------------------------------------------- |
| mov dx, 0x00<br />int 0x21<br />mov ah, 0x4c<br />int 0x21 | 66 BA 00 00 CD 21 B4 4C CD 21 | 0110 0110 1011 1010 0000 0000 0000 0000 1100 1101 0010 0001 1011 0100 0100 1100 1100 1101 0010 0001 |

So what assembler does is takes that human readable part and converts it into a legit byte code. It's not too hard to see. mov dx, 0x00 becomes 66 BA 00 00, int 0x21 becomes CD 21 and so on, its that int 0x21 is easier to read for us than CD21. Catch here is depending on the ISA(Industry Standard Architecture. eg. arm64, x86) you are using, different ISA's have different instructions. So you need a separate assemby and separate resulting bytecodes for different processors architectures. For example x64 is extended x86 with more instructions and 64 bit registers. This is why when you download furry hentai games from itch.io they have x64 and x86 version, x86 does not have some shit that x64 has so it won't run... That's why all this Apple M1 silicon and it being able to run x64 is pretty poggers as they added some x64 instructions emulation extensions to their arm64 CPU. Obviously it ain't as fast as the real deal but it's good enough to be runnable. Theres also open-source version of running x86 and x64 on arm called Box86 and Box64, Microsoft also has their implementation. Im not sure, but I suppose you could call CUDA an ISA too, as you need a special compiler for it, but don't quote me on that.

You should also learn about linkers!
