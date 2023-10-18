This repository includes a notebook file that leverages the airpls package (available at https://code.google.com/p/airpls) to perform baseline correction on Raman signals. Furthermore, this code effectively eliminates spikes from the Raman signal. Following noise removal, the data is then normalized using the standard normal variate method, that is, subtracting each spectrum by its mean value and dividing by the standard deviation for further analysis.


As an example, the raw Raman spectrum without baseline correction and denoising is shown below.

![download](https://github.com/ArezooArdekani/Raman_spcetroscopy_baseline_correction/assets/94130390/c6a89e0e-d73b-4053-b06b-a0e73a1382d1)

After baseline correction and removal of the spikes, the Raman spectrum would look like below.
![download (1)](https://github.com/ArezooArdekani/Raman_spcetroscopy_baseline_correction/assets/94130390/73b84706-0768-401b-925e-8dfe59c9eddd)

Furthermore after normalizing the spectrum would look like below. 
