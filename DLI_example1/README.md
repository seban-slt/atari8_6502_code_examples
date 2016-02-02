This e- [x]ample show, the use of *Display List Interrupts* technique to achieve more colours on screen.

The picture used in e- [x]ample is 160p- [x] * 240p- [x] and uses ANTIC $0E graphics mode (2 bit per pi- [x]el, 4 colours, 2:1 pi- [x]el proportion).

The DLI is used to change the three play-field colour registers during each occurrence of DLI, this will allow to show more colours on screen.

The e- [x]ample shows the "daisy chaining" of DLI routines, at end of each routine the DLI vector is changed to ne- [x]t DLI routine. So the ne- [x]t occurrence of Display List Interrupt will cause the e- [x]ecution of the new DLI routine.

TO DO:

- [x] ~~change the addresses of registers to their names (sorry, but I remember the addresse
s of each hardware register directly, so I don't bother to remember their names)~~ mostly 
done by @skrzyp, needs review from @seban-slt.

