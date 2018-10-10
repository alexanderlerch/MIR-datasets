---
ID: 527
post_title: exercises
author: Alex
post_excerpt: ""
layout: page
permalink: >
  https://www.audiocontentanalysis.org/teaching/exercises/
published: true
post_date: 2013-08-25 14:29:17
---
This page will provide a growing list of exercises and assignments.
<h2>Chapter 2</h2>
<ol>
 	<li>
<h4><strong>Spectrogram</strong></h4>
Write a function that plots a spectrogram-representation of an audio file (hint: use Matlab's <code>image</code> function). Use a von-Hann window and allow a user-definable block length and hop length. Make sure the axes are showing correct time and frequency scales in seconds and frequency, respectively.</li>
</ol>
<h2>Chapter 4</h2>
<ol>
 	<li>
<h4><strong>Peak Program Meter</strong></h4>
<ol>
 	<li>Implement the PPM as shown in Fig. 4.5</li>
 	<li>Choose an attack time of 10ms and a release time of 1.5s and compute the coefficients according to Eq. (4.10).</li>
 	<li>Choose a step function as the input signal and compute the output signal to verify proper implementation.</li>
 	<li>Implement a peak envelope feature by taking the absolute maximum of each block.</li>
 	<li>Compute the two outputs for an audio file. Discuss the differences.</li>
</ol>
</li>
</ol>
<h2>Chapter 7</h2>
<ol>
 	<li>
<h4><strong>Simple Classifier</strong></h4>
<ol>
 	<li>Implement the following features:
<ul>
 	<li>Spectral Centroid</li>
 	<li>Zero Crossing Rate</li>
 	<li>Spectral Crest Factor</li>
 	<li>Spectral Flux</li>
 	<li>RMS</li>
</ul>
</li>
 	<li>For each file, compute the subfeatures mean and standard deviation. Normalize the features.</li>
 	<li>Download the <a title="GTZAN dataset" href="http://marsyas.info/downloads/datasets.html" target="_blank">GTZAN dataset</a></li>
 	<li>Implement a kNN Classifier</li>
 	<li>Do a sequential forward selection on the features with k=3, plot the classification accuracy depending on the results</li>
 	<li>Evaluate the accuracy with 10-fold cross-validation</li>
</ol>
</li>
 	<li>
<h4><strong>KMeans</strong></h4>
Implement a matlab function: (clusterIdx, centroids) = myKMeans(X, K) in which X is the input data matrix, K is the parameter k, clusterIdx is the clustering labels for all samples, and centroids are the k centroids after the clustering.
<ul>
 	<li>Run an experiment on a well-known dataset and visualize your clusters:
<ul>
 	<li>in the matlab command window, use load fisheriris.mat. 'meas' is a 150 by 4 feature matrix. 'species' is a 150 by 1 feature vector, and it is also the ground truth of the data</li>
 	<li>perform k-means on the data</li>
 	<li>select two features, visualize your result using scatter(). Make sure that you use different colors for different clusters.</li>
</ul>
</li>
 	<li>Evaluation: use the ground truth compute Precision and Recall for each cluster.</li>
</ul>
</li>
</ol>