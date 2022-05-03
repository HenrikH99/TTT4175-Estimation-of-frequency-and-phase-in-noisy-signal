# TTT4175-Estimation-of-frequency-and-phase-in-noisy-signal
Project in the course TTT4175 Estimation, Detection and Classification, written by Wilhelm A. Kristiansen and Henrik P. Hemnes

A noisy signal is generated and the FFT of the signal is performed to try and estimate the frequency and phase. The estimate accuracy will vary with the varying signal-to-noise ratio. Another method uses the Nelder-Mead algorith to try and finetune the estimate with a small FFT size.

# Running the program
Simply run ```python3 estimation_project``` to start the simulation. You can also open it in your IDE of choise and run it from there

It will by default run 100 iterations for each FFT size, and will only run for k=10, k=20 and k=10 with Nelder-Mead. These values can be changed by changing the variable ```iterations```, ```step``` which is the number increase between 10 and 20. You can also save the simulated values by setting the flag ```write_to_file``` to ```True```. If you write the reults to a file the files will be located in the folder ```results```.
