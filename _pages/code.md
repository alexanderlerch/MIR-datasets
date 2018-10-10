---
ID: 30
post_title: code
author: Alex
post_excerpt: ""
layout: page
permalink: >
  https://www.audiocontentanalysis.org/code/
published: true
post_date: 2012-06-16 16:58:28
---
On this page you can find code snippets and examples for algorithms presented in the book. Please note that the provided code examples as matlab functions are only intended to showcase algorithmic principles - they are not suited to be used without parameter optimization and additional algorithmic tuning.

The majority of these Matlab sources require the <a title="Matlab Signal Processing Toolbox" href="http://www.mathworks.de/products/signal/" target="_blank">Matlab Signal Processing Toolbox</a> installed. Several scripts (such as MFCCs and Gammatone filters) are based on implementations in Slaney's <a title="Auditory Toolbox" href="https://engineering.purdue.edu/~malcolm/interval/1998-010/" target="_blank">Auditory Toolbox</a>.

All m-files can be downloaded directly from <a title="ACA: Matlab Sources" href="https://github.com/alexanderlerch/ACA-Code">this github repository</a>.

Please feel free to submit comments and code (snippets) that might improve the usefulness of this code and website anytime.
<ul>
	<li><strong>instantaneous features</strong> [entry point <a title="feature computation" href="http://www.audiocontentanalysis.org/code/audio-features/computefeature/">ComputeFeature</a>]
<ul>
	<li><em>frequency domain</em>
<ul>
	<li><a title="mel frequency cepstral coefficients" href="http://www.audiocontentanalysis.org/code/audio-features/mel-frequency-cepstral-coefficients/">Mel Frequency Cepstral Coefficients</a> (Sect. 3.3.7)</li>
	<li><a title="pitch chroma" href="http://www.audiocontentanalysis.org/code/audio-features/pitch-chroma/">Pitch Chroma</a> (Sect. 5.5.1)</li>
	<li><a title="spectral centroid" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-centroid/">Spectral Centroid</a> (Sect. 3.3.3)</li>
	<li><a title="spectral crest" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-crest/">Spectral Crest</a> (Sect. 3.4.1.1)</li>
	<li><a title="spectral decrease" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-decrease/">Spectral Decrease</a> (Sect. 3.3.5)</li>
	<li><a title="spectral flatness" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-flatness/">Spectral Flatness</a> (Sect. 3.4.1.2)</li>
	<li><a title="spectral flux" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-flux/">Spectral Flux </a>(Sect. 3.3.2)</li>
	<li><a title="spectral kurtosis" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-kurtosis/">Spectral Kurtosis</a> (Sect. 3.2.8.1)</li>
	<li><a title="spectral rolloff" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-rolloff/">Spectral Rolloff</a> (Sect. 3.3.1)</li>
	<li><a title="spectral skewness" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-skewness/">Spectral Skewness</a> (Sect. 3.2.7.1)</li>
	<li><a title="spectral slope" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-slope/">Spectral Slope</a> (Sect. 3.3.6)</li>
	<li><a title="spectral spread" href="http://www.audiocontentanalysis.org/code/audio-features/spectral-spread/">Spectral Spread</a> (Sect. 3.3.4)</li>
	<li><a title="tonal power ratio" href="http://www.audiocontentanalysis.org/code/audio-features/tonal-power-ratio/">Tonal Power Ratio</a> (Sect. 3.4.1.3)</li>
</ul>
</li>
</ul>
<ul>
	<li><em>time domain</em>
<ul>
	<li><a title="autocorrelation coefficient(s)" href="http://www.audiocontentanalysis.org/code/audio-features/autocorrelation-coefficients/">Autocorrelation Coefficients</a> (Sect. 3.4.2)</li>
	<li><a title="autocorrelation maximum" href="http://www.audiocontentanalysis.org/code/audio-features/autocorrelation-max/">Autocorrelation Maximum</a> (Sect. 3.4.1.4)</li>
	<li><a title="peak envelope" href="http://www.audiocontentanalysis.org/code/audio-features/peak-envelope/">Peak Envelope</a> (Sect. 4.4)</li>
	<li><a title="predictivity ratio" href="http://www.audiocontentanalysis.org/code/audio-features/predictivity-ratio/">Predictivity Ratio</a> (Sect. 3.4.1.5)</li>
	<li><a title="root mean square" href="http://www.audiocontentanalysis.org/code/audio-features/rms/">Root Mean Square</a> (Sect. 4.3.1)</li>
	<li><a title="standard deviation" href="http://www.audiocontentanalysis.org/code/audio-features/standard-deviation/">Standard Deviation</a> (Sect. 3.2.6)</li>
	<li><a title="zero crossing rate" href="http://www.audiocontentanalysis.org/code/audio-features/zero-crossing-rate/">Zero Crossing Rate</a> (Sect. 3.4.3)</li>
</ul>
</li>
</ul>
</li>
	<li><strong>pitch tracking</strong> [entry point <a title="fundamental frequency computation" href="http://www.audiocontentanalysis.org/code/pitch-tracking/compute-pitch/">ComputePitch</a>]
<ul>
	<li><em>frequency domain</em>
<ul>
	<li><a title="harmonic product spectrum" href="http://www.audiocontentanalysis.org/code/pitch-tracking/hps/">Harmonic Product Spectrum</a> (Sect.5.3.3.5)</li>
	<li><a title="spectral autocorrelation" href="http://www.audiocontentanalysis.org/code/pitch-tracking/spectral-autocorrelation/">Spectral Autocorrelation</a> (Sect. 5.3.3.6)</li>
</ul>
</li>
	<li><em>time domain</em>
<ul>
	<li><a title="auditory pitch tracking approach" href="http://www.audiocontentanalysis.org/code/pitch-tracking/auditory-pitch-tracking-approach/">Auditory Approach</a> (Sect. 5.3.3.8)</li>
	<li><a title="autocorrelation function" href="http://www.audiocontentanalysis.org/code/pitch-tracking/acf/">Autocorrelation Function</a> (Sect. 5.3.3.2)</li>
	<li><a title="average magnitude difference function" href="http://www.audiocontentanalysis.org/code/pitch-tracking/amdf/">Average Magnitude Difference Function</a> (Sect. 5.3.3.3)</li>
	<li><a title="zero crossings" href="http://www.audiocontentanalysis.org/code/pitch-tracking/zero-crossings/">Zero Crossings</a> (Sect. 5.3.3.1)</li>
</ul>
</li>
</ul>
</li>
	<li><strong>key detection</strong>
<ul>
	<li><a title="key detection" href="http://www.audiocontentanalysis.org/code/key-detection/key-detection/">Simple Key Detection</a> (Sect. 5.5)</li>
</ul>
</li>
	<li><strong>onsets and tempo</strong>
<ul>
	<li>Novelty Function [entry point <a title="novelty function computation" href="http://www.audiocontentanalysis.org/code/rhythm/novelty-function-computation/">ComputeNoveltyFunction</a>]
<ul>
	<li><a title="novelty function: flux" href="http://www.audiocontentanalysis.org/code/rhythm/novelty-function-computation/novelty-function-flux/">Flux</a> (Sect. 6.3.1)</li>
	<li><a title="novelty function: hainsworth" href="http://www.audiocontentanalysis.org/code/rhythm/novelty-function-computation/novelty-function-hainsworth/">Hainsworth</a> (Sect. 6.3.1)</li>
	<li><a title="novelty function: laroche" href="http://www.audiocontentanalysis.org/code/rhythm/novelty-function-computation/novelty-function-laroche/">Laroche</a> (Sect. 6.3.1)</li>
</ul>
</li>
	<li><a title="simple beat histogram computation" href="http://www.audiocontentanalysis.org/code/rhythm/beat-histogram/">Simple Beat Histogram</a> (Sect. 6.4)</li>
</ul>
</li>
	<li><strong>helper functions</strong>
<ul>
	<li><a title="frequency to bark conversion" href="http://www.audiocontentanalysis.org/code/helper-functions/frequency-to-bark-conversion/">Conversion: Frequency to Bark Scale</a> (Sect. 5.1.1.2)</li>
	<li><a title="frequency to mel conversion" href="http://www.audiocontentanalysis.org/code/helper-functions/frequency-to-mel-conversion/">Conversion: Frequency to Mel Scale</a> (Sect. 5.1.1.1)</li>
	<li><a title="frequency to MIDI pitch conversion" href="http://www.audiocontentanalysis.org/code/helper-functions/frequency-to-midi-pitch-conversion/">Conversion: Frequency to MIDI Pitch</a> (Sect. 5.2.5)</li>
	<li><a title="MIDI pitch to frequency conversion" href="http://www.audiocontentanalysis.org/code/helper-functions/midi-pitch-to-frequency-conversion/">Conversion: MIDI Pitch to Frequency</a> (Sect. 5.2.5)</li>
	<li><a title="gammatone filterbank" href="http://www.audiocontentanalysis.org/code/helper-functions/gammatone-filterbank/">Gammatone Filterbank</a> (Sect. 2.2.5.1)</li>
	<li><a title="simple DTW" href="http://www.audiocontentanalysis.org/code/helper-functions/dtw/">Dynamic Time Warping</a> (Sect. 7.1)</li>
</ul>
</li>
</ul>