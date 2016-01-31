This example shows how the PLOT function in hi-res monochromatic mode can be implemented.

Source contains two procedures... one is the slow version, but this shows the principles of operation. The second version is based on Lookup Tables, and show that using of LUT's can speed-up the code execution. Both implemented procedures arranged to run in controlled environment, and the number of plotted points in certain amount of time is calculated.

TO DO:

- change the addresses of registers to their names (sorry, but I remember the addresses of each hardware register directly, so I don't bother to remember their names).
