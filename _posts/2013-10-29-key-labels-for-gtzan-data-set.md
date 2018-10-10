---
ID: 617
post_title: Key labels for GTZAN data set
author: Alex
post_excerpt: ""
layout: post
permalink: >
  https://www.audiocontentanalysis.org/2013/10/key-labels-for-gtzan-data-set/
published: true
post_date: 2013-10-29 14:50:25
---
The <a title="GTZAN download" href="http://marsyas.info/downloads/datasets.html" target="_blank">GTZAN data set</a> is probably one of the most prominent data sets used in research related to Music Information Retrieval and Audio Content Analysis. The data set contains 1000 excerpts from songs, sorted into 10 genres.

While this set is old and it is clear that it <a title="An Analysis of the GTZAN Music Genre Dataset" href="http://up.stevetjoa.com/p7.pdf" target="_blank">has its disadvantages </a>[1], it is a well-known, widely-used, and, last but not least, easily available set. This is why I chose this data set to annotate the musical keys of the excerpts. The complete annotation can be found <a title="GTZAN key labels" href="https://github.com/alexanderlerch/data_set" target="_blank">here</a>.
<h2>Procedure</h2>
I used my tuning fork to identify the key of each song. I did <em>not</em> label excerpts that
<ul>
	<li>included modulations, or</li>
	<li>were particularly difficult to identify.</li>
</ul>
<strong>Statistics</strong>

[table]
Genre, Major Keys, Minor Keys, # annotated
blues, 3,95,98
classic,0,0,0
country, 94,5,99
disco, 43,55,98
hiphop,13,68,81
jazz,52,27,79
metal,4,89,93
pop,44,50,94
reggae,53,44,97
rock,55,43,98

[/table]
<h2>Applications</h2>
Besides the obvious application of directly evaluating key detection systems, we used this data set also for an indirect evaluation of a <a title="The Tonalness Spectrum: Feature-Based Estimation of Tonal Components" href="http://dafx13.nuim.ie/papers/03.dafx2013_submission_48.pdf" target="_blank">detection of tonal components</a> in a spectrum [2].
<h2>References</h2>
[1] Sturm, Bob: <em>An Analysis of the GTZAN Music Genre Dataset</em>, Proceedings of the 2nd <b>International ACM Workshop on Music Information Retrieval with User-Centered and Multimodal Strategies</b> (MIRUM), Nara, Japan, November, 2012

[2] Kraft, Sebastian; Lerch, Alexander, Zoelzer, Udo: <em>The Tonalness Spectrum: Feature-Based Estimation of Tonal Components</em>, Proc. of the 16th Int. Conference on Digital Audio Effects (DAFx), Maynooth, Ireland, September 2-5, 2013

&nbsp;