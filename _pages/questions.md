---
ID: 1101
post_title: questions
author: Alex
post_excerpt: ""
layout: page
permalink: >
  https://www.audiocontentanalysis.org/teaching/questions/
published: true
post_date: 2015-11-07 20:17:01
---
This page will provide a growing list of questions.
<h2>Chapter 2</h2>
<ol>
 	<li>
<h4><strong>Periodic Signals</strong></h4>
Do you know the basics? Take a <a href="https://frama.link/ACA_Chap2-PeriodicSignals" target="_blank">quick test</a>!</li>
 	<li>
<h4><strong>Probability Density Function</strong></h4>
What is the advantage of describing signals with their PDF. What information is lost?</li>
 	<li>
<h4><strong>Fourier Series</strong></h4>
Have you understood the fundamental properties of the Fourier Series? Take <a href="https://frama.link/ACA_Chap2-FourierSeries" target="_blank">the test</a>!</li>
 	<li>
<h4><strong>Quantization</strong></h4>
Draw the PDF shape of the quantization error (signal variance much higher than quantizer step size). Label the axes and annotate x and y values</li>
 	<li>
<h4><strong>Sampling</strong></h4>
What is the maximum bandwidth of a signal sampled with a rate of 24kHz?</li>
 	<li>
<h4><strong>Sampling</strong></h4>
A sinusoidal is sampled at a sampling frequency of 6 kHz. Which of the following frequencies will produce a 1 kHz sinusoidal in the reconstructed base band (starting at 0Hz)?
<ul>
 	<li>4</li>
 	<li>7</li>
 	<li>15</li>
 	<li>5</li>
</ul>
</li>
 	<li>
<h4><strong>Sampling</strong></h4>
Why is the sampling rate for speech lower, in general, than the sampling rate for music?
<ul>
 	<li>On average, the bandwidth for speech signals is less than the bandwidth for musical signals.</li>
 	<li>Speech is monophonic (Single voiced).</li>
 	<li>Speech has a lower dynamic range than music.</li>
 	<li>The sampling rate for music and speech is always the same. The statement is incorrect.</li>
</ul>
</li>
 	<li>
<h4><strong>Sampling</strong></h4>
Mark the following statements as true or false.
<ul>
 	<li>An anti-aliasing filter is used to limit the bandwidth of a signal to within half the sampling frequency.</li>
 	<li>Perfect reconstruction of a continuous signal is possible as long as its bandwidth is lower than the sampling rate.</li>
</ul>
</li>
 	<li>
<h4><strong>Quantization &amp; Sampling</strong></h4>
Mark the statements that are correct.
<ul>
 	<li>In theory, a quantized signal can be perfectly reconstructed if the word length is at least twice the maximum amplitude.</li>
 	<li>A sampled signal has a periodic spectrum.</li>
 	<li>The quantization error is always in the range of [-Delta/2;Delta/2] (Delta is the quantization step size).</li>
 	<li>Increasing the quantizer word length from w=4 bit to w=8 bit will increase the SNR by 6dB.</li>
</ul>
</li>
 	<li>
<h4><strong>Moving Average Filter</strong></h4>
A Moving Average Filter of length N is applied two times (in series) to an audio signal. Describe length and shape of the impulse response of an FIR filter resulting in the same output when only applied once.</li>
 	<li>
<h4><strong>Correlation coefficient</strong></h4>
Two signals have a (normalized) correlation coefficient of -1. What does that imply?</li>
 	<li>
<h4><strong>Correlation coefficient</strong></h4>
What will be the (normalized) correlation coefficient of a sine wave with frequency 'f' and another sine wave with the same frequency but a phase-shift of pi radians?
<ul>
 	<li>0</li>
 	<li>-1</li>
 	<li>0.5</li>
 	<li>1</li>
</ul>
</li>
 	<li>
<h4><strong>Correlation function</strong></h4>
Draw the shape of the correlation function between a sawtooth signal and white noise.</li>
 	<li>
<h4><strong>Correlation function</strong></h4>
You compute the correlation function of two signal blocks with the lengths 1024 and 2048, respectively. What is the length of the result?</li>
 	<li>
<h4><strong>Autocorrelation</strong></h4>
Mark the statements that are correct.
<ul>
 	<li>the ACF is always positive</li>
 	<li>the ACF is symmetric around lag 0</li>
 	<li>the Fourier transform of the ACF is real-valued</li>
 	<li>the ACF of a periodic signal is periodic</li>
 	<li>the ACF is always periodic</li>
 	<li>the ACF of a periodic signal is maximum at lag 0</li>
</ul>
</li>
 	<li>
<h4><strong>Autocorrelation</strong></h4>
Take a recording (ca. 15-30s) of a single-voiced instrument or vocals. Then,
<ul>
 	<li>compute the block-wise autocorrelation function with Matlab's <code>xcorr</code> function (block length: 4096, hop length: 256),</li>
 	<li>compare the results with your own implementation,</li>
 	<li>create a function which finds the ACF maximum after the first zero crossing and returns all maxima indices for all blocks in a vector, and</li>
 	<li>plot and discuss/interpret the results.</li>
</ul>
</li>
 	<li>
<h4><strong>Convolution in the frequency domain</strong></h4>
You have a signal block <code>x</code> and an impulse response <code>h</code>, both of the same length (1024) and you want to compute the convolution result. Knowing that convolution via the FFT might be more efficient than in the time domain, you implement the following script:
<pre lang="matlab">X = fft(x);
H = fft(h);

Y = X.*H;
y = ifft(Y);</pre>
Discuss why the result is not the expected convolution result and modify the code so that it produces the correct result as computed by the Matlab function 'conv'.</li>
 	<li>
<h4><strong>Convolution</strong></h4>
Sketch the output of the convolution of the two pairs of signals below. Make sure to properly label axes and mark important axis points.

<a href="http://www.audiocontentanalysis.org/wp-content/uploads/convolution_exercise.png"><img class="aligncenter wp-image-1216 size-full" src="http://www.audiocontentanalysis.org/wp-content/uploads/convolution_exercise.png" width="624" height="102" /></a></li>
 	<li>
<h4><strong>Convolution</strong></h4>
Describe the following properties of the convolution operation and give an example of the practical meaning in an audio processing context.
<ul>
 	<li>(g(t)*h(t))*x(t) = g(t)*(h(t)*x(t))</li>
 	<li>g(t)*(h(t)+x(t)) = (g(t)*h(t))+(g(t)*x(t))</li>
</ul>
</li>
 	<li>
<h4><strong>Correlation and Convolution 1</strong></h4>
Both the convolution and the correlation operation can be calculated in the frequency domain by multiplication. Discuss the differences in the frequency domain and how they relate to the time domain equations.</li>
 	<li>
<h4><strong>Correlation and Convolution 2</strong></h4>
Name 2 pairs of signals: (1) the correlation function between those signals equals the output of their convolution, (2) the correlation function between those signals and the output of their convolution is different.</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
Name 3 important properties of the Fourier Transform and briefly discuss them.</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
Given that the Fourier transform of x(t) is X(jomega), what is the Fourier transform of x(t-T0)?</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
Each of the following magnitude spectra has a corresponding time domain signal. Give the correct grouping (e.g., 1A, 2B, etc.).

<a href="http://www.audiocontentanalysis.org/wp-content/uploads/Fourier_exercise.png"><img class="aligncenter size-full wp-image-1221" src="http://www.audiocontentanalysis.org/wp-content/uploads/Fourier_exercise.png" alt="" width="286" height="294" /></a></li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
What is the FT of two delta functions located symmetrically around 0?</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
The Fourier transform of a rectangular window is WR(jomega). Given basic operations like duplication, multiplication, addition, convolution, time-scaling, etc., how do you derive the shape Fourier transform of a triangular window? What is the result?</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
Which of the following statements are correct:
<ul>
 	<li>FT and DFT are both discrete in the time domain</li>
 	<li>a complete description of the spectrum contains both magnitude and phase</li>
 	<li>The distance between two neighboring frequency bins (in Hz) inreases as the DFT block block length increases</li>
 	<li>The FTs of a cosine and a sine with the same frequency are identical.</li>
 	<li>The FT of a real signal is symmetric.</li>
 	<li>The FT will be compressed as the time domain signal is stretched.</li>
 	<li>An impulse response is completely defined and can be perfectly reconstructed given its FT.</li>
</ul>
</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
What happens to the Fourier Transform of a signal if it is multiplied with a cosine wave with non-zero frequency?
<ul>
 	<li>The FT gets shifted along the frequency axis.</li>
 	<li>The FT remains unchanged.</li>
 	<li>The frequency axis of the FT gets scaled.</li>
 	<li>The Fourier Transform is inverted around the frequency axis.</li>
</ul>
</li>
 	<li>
<h4><strong>Fourier transform</strong></h4>
Mark the following statements as true or false:
<ul>
 	<li>The magnitude spectrum of a real-valued signal is symmetric about the y-axis.</li>
 	<li>The real part of the FT is always positive.</li>
 	<li>The FT will be compressed along the frequency axis as the time domain signal is stretched.</li>
 	<li>The FT of an impulse response describes a system as completely as the impulse response itself.</li>
 	<li>The energy of the time-domain signal is preserved in the frequency domain.</li>
</ul>
</li>
 	<li>
<h4><strong>Time-Frequency transformations</strong></h4>
Name one advantage and one disadvantage of the Constant Q Transform as compared to the DFT.</li>
 	<li>
<h4><strong>Cepstrum</strong></h4>
Mark the statements that are correct.
<ul>
 	<li>The basic signal model for the input signal of a cepstral analysis is x(t) = e(t) + h(t) (e(t): excitation signal, h(t) transfer function)</li>
 	<li>The cepstrum has a non-linear frequency scale</li>
 	<li>The cepstrum can be used for, amongst others, pitch detection and spectral envelope extraction</li>
 	<li>The human voice fits the basic signal model of the cepstrum well.</li>
</ul>
</li>
</ol>
<h2>Chapter 3</h2>
<ol>
 	<li>
<h4><strong>Feature Normalization</strong></h4>
You extracted 5 features (spectral centroid, spectral crest, spectral flatness, zero crossing rate as introduced in the text book) and want to use a NN (Nearest Neighbor) classifier with a Euclidean distance metric. Mark the correct statements below.
<ul>
 	<li>all of the mentioned features are in a similar numerical range</li>
 	<li>PCA (Principle Component Analysis) should be applied for feature normalization</li>
 	<li>z-score normalization will result in a numerical range from -1 to 1 for each feature</li>
 	<li>The classification performance will be affected by the feature normalization process</li>
</ul>
</li>
 	<li>
<h4><strong>Feature Selection</strong></h4>
Consider a classification task using a set of 3 features X1, X2, X3. The classification accuracy for different feature combinations are shown in the following table.
[table]
feature combinations, classification accuracy
(X1), 50%
(X2), 55%
(X3), 60%
(X1;X2), 74%
(X1;X3), 65%
(X2;X3), 66%
[/table]
<ol>
 	<li>Describe the process/the processing steps of Sequential Forward Selection.</li>
 	<li>Based on this selection, which two features will be selected?</li>
</ol>
</li>
 	<li>
<h4><strong>Feature Design</strong></h4>
Discuss advantages and disadvantages of using unsupervised Feature Learning approaches as compared to 'traditional' hand-crafted features.</li>
 	<li>
<h4><strong>Dimensionality</strong></h4>
Given a finite number of observations, is it true that increasing the number of features always leads to an improved classification accuracy. Why or why not?</li>
</ol>
<h2>Chapter 5</h2>
<ol>
 	<li>
<h4><strong>Pitch perception</strong></h4>
Describe the relation of the pitch perception dimensions tone height and chroma.</li>
 	<li>
<h4><strong>MIDI Pitch</strong></h4>
Given the A4 has the MIDI pitch index 69, what is the index of C5?</li>
 	<li>
<h4><strong>Cents</strong></h4>
How do you compute the distance of two frequencies f1, f2 as pitch difference? Derive given m(f) = 69+12ld(f/fA4).</li>
 	<li>
<h4><strong>Cents</strong></h4>
Mark the correct statements below.
<ul>
 	<li>Cent is relative to the ratio between two pitches</li>
 	<li>The distance in Cents between the pitches E4 and F4 is 100 cents</li>
 	<li>The distance in Cents between the pitches E2 and G2 equals the distance between E4 and G4.</li>
 	<li>To compute the distance of two frequencies in cent, the reference tuning frequency is required (e.g., A4=440Hz).</li>
</ul>
</li>
 	<li>
<h4><strong>Frequency Reassignment</strong></h4>
Mark the correct statements below.
<ul>
 	<li>The derivative of the phase with respect to time referred to as the instantaneous frequency.</li>
 	<li>The sampling rate has to be known to compute the instantaneous frequency in Hz.</li>
 	<li>If the hopsize is small enough, phase unwrapping is no longer needed.</li>
 	<li>The instantaneous frequency estimation might be wrong if there are multiple sources overlapping in the frequency domain.</li>
</ul>
</li>
</ol>
<h2>Chapter 6</h2>
<ol>
<ol>
 	<li>
<h4><strong>Definition</strong></h4>
Describe the difference between an 'onset' and a 'beat'.</li>
 	<li>
<h4><strong>Inter-Onset-Interval</strong></h4>
You extracted an IOI-histogram with two distinct peaks (at 166.67ms and 333.33ms, respectively).
<ul>
 	<li>Explain why there might be two peaks in the histogram.</li>
 	<li>What is the most likely tempo estimate given this histogram?</li>
</ul>
</li>
</ol>
</ol>
&nbsp;