This example show, the use of *Display List Interrupts* technique to achieve more colours on screen.

The picture used in example is 160px * 240px and uses ANTIC $0E graphics mode (2 bit per pixel, 4 colours, 2:1 pixel proportion).

The DLI is used to change the three play-field colour registers during each occurrence of DLI, this will allow to show more colours on screen.

The example shows the "daisy chaining" of DLI routines, at end of each routine the DLI vector is changed to next DLI routine. So the next occurrence of Display List Interrupt will cause the execution of the new DLI routine.

TO DO:

- [x] ~~change the addresses of registers to their names (sorry, but I remember the addresses of each hardware register directly, so I don't bother to remember their names)~~ mostly done by @skrzyp, needs review from @seban-slt.

