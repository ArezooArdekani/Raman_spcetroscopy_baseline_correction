This repository includes a notebook file that leverages the airpls package (available at https://code.google.com/p/airpls) to perform baseline correction on Raman signals. Furthermore, this code effectively eliminates spikes from the Raman signal. Following noise removal, the data is then normalized using the standard normal variate method, that is, subtracting each spectrum by its mean value and dividing by the standard deviation for further analysis.

For example, the below figure shows the Raw Raman spectrum that requires baseline correction and denoising

![download](https://github.com/ArezooArdekani/Raman_spcetroscopy_baseline_correction/assets/94130390/2eff08a6-0fba-4852-af0c-d85e6a91db91)
