Objectives of the project:
Time sequence analysis on Schlieren imaging using wavelet transform to analyze the frequency change at different locations of the nozzle of the propulsion system.
Method:
A spectral and wavelet analysis is performed on the Schlieren images in terms of pixel intensity for each pixel independently.
The study shows that at positions close to the nozzle the frequency is higher compared to locations farther from the vortex. In this work, we further try to
understand the frequency with respect to the time with the help of a spectrogram.

Dataset: A private dataset of IIST and ISRO was used for evaluation. Schlieren imaging method is used to visualize changes in shock waves, fluid flows, and heat transfer.
The dimensions of the grayscale images are 1024x1024.

Date processing: Fourier Transform was used to separately analyze the signal vector.

Method: 
Spectral Analysis performed using Fast Fourier Transform. his computes the frequency components of the time signal. The x-axis of a temporal signal is time while the
y-axis is the intensity at a particular pixel point of all the images. Power Spectral Density(PSD) is also computed for analysis.
Wavelet Analysis: Spectral analysis shows almost accurate results for signals with periodic components. However, the signal is not always fully periodic, as noise is bound to be
present at certain frequencies in time. Therefore a wavelet transform is performed to keep the discretization in time. The initial signal is decomposed using the
continuous wavelet transform. Morlet Wavelet and Paul wavelet is used for wavelet analysis.



