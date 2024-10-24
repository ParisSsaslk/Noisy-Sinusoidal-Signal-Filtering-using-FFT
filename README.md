# Noisy-Sinusoidal-Signal-Filtering-using-FFT
This repository contains a Python script that demonstrates how to generate a noisy sinusoidal signal, apply Fast Fourier Transform (FFT) to filter out unwanted frequencies, and visualize the results. The main goal is to show how to use frequency domain filtering to clean noisy signals, which is a common task in signal processing.

## Features
Generate a noisy sinusoidal signal using a combination of a sine wave and random noise.
Perform FFT to convert the signal to the frequency domain.
Apply a low-pass filter to remove high-frequency noise.
Visualize the original signal, frequency spectrum, and the filtered signal.
Use inverse FFT to transform the filtered signal back to the time domain.

## Code Structure
The script follows these key steps:

### 1. Generate Noisy Signal:
- Create a sinusoidal signal with added random noise.
- Plot the noisy signal to visualize the noise impact.

### 2. Fast Fourier Transform (FFT):
- Convert the noisy signal into the frequency domain using fftpack.fft.
- Compute the amplitude of the signal’s frequency components.

### 3. Filter Design:
Implement a low-pass filter that removes high-frequency components from the signal, retaining only frequencies below 5 Hz.

### 4. Inverse FFT:
Convert the filtered frequency-domain signal back to the time domain using ifft to obtain the denoised signal.

### 5. Visualization:
Plot the original signal, the amplitude spectrum of both the unfiltered and filtered signals, and the final filtered signal over the original noisy signal.

## Output
The script will generate the following visualizations:
- The original noisy sinusoidal signal.
- The frequency spectrum of the original signal.
- The filter response in the frequency domain.
- The filtered signal in both the frequency and time domains.
