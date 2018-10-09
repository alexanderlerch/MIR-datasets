---
ID: 430
post_title: errata
author: Alex
post_excerpt: ""
layout: page
permalink: >
  https://www.audiocontentanalysis.org/errata/
published: true
post_date: 2013-02-12 18:03:56
---
Please contact me if you find any mistakes and errors in the book; I will add them to this (hopefully slowly) growing list of corrections for the 1st edition.

[table]
Section, Page, Wrong, Corrected
2.1.3.1,10,"A sampled signal can only be reconstructed without loss of information if the sample rate $f_{\mathrm{S}}$ is higher than twice the highest frequency $f_{\mathrm{max}}$ in the sampled audio signal.","A sampled signal can only be reconstructed without loss of information if the sample rate $f_{\mathrm{S}}$ is higher than twice the <strong>bandwidth</strong> $f_{\mathrm{max}}$ of the audio signal."
2.1.4.1,13, "The abscissa of a PDF plot represents all possible amplitude values of the signal $x$ and their probability is plotted on the ordinate.","The abscissa of a PDF plot represents all possible (amplitude) values of the signal $x$ and their probability <strong>density</strong> is plotted on the ordinate."
2.2.3,20,<code>\Delta\Omega = \frac{2\pi}{\mathcal{K}\cdot T_{\mathrm{S}}}</code>,<code>\Delta\Omega = \frac{2\pi}{\mathcal{K}}</code>
,20,<code>f(k) = <code>\frac{\Delta\Omega}{2\pi}k = \frac{f_{\mathrm{S}}}{\mathcal{K}}k</code>,<code>f(k) = \frac{\Delta\Omega}{2\pi}k f_{\mathrm{S}} = \frac{k}{\mathcal{K}}f_{\mathrm{S}}</code>
2.2.4,24,"Q adjusts the desired frequency resolution per octave c, while ...","Q adjusts the desired frequency resolution and can be derived from c, the desired number of frequency bins per octave, while ..."
2.2.6.4,28,<code>r_{xx}(\tau) &amp;=&amp; \int\limits_{-\infty}^{\infty}{x(\tau)\cdot x(t+\tau)\, d\tau} \\ &amp;=&amp; x(\tau) \ast x(-\tau)</code>,<code>r_{xx}(<strong>t</strong>) &amp;=&amp; \int\limits_{-\infty}^{\infty}{x(\tau)\cdot x(t+\tau)\, d\tau} \\ &amp;=&amp; x(<strong>t</strong>) \ast x(<strong>-t</strong>)</code>
3,32,"Envelope of excerpts from a typical speech recording (left), a string quartet recording (mid), and a pop recording (right)  with a length of \unit[15]{s}","Waveform of excerpts from a pop recording (left), a string quartet recording (mid), and a speech recording (right)  with a length of \unit[15]{s}, respectively"
3.2,35,"Various methods describing the properties of a (time-invariant) properties of a signal...","Various methods describing the properties of a (stationary) signal..."
3.3.3.1,46,denominator: <code>\sum\limits_{k = 0}^{N/2-1}{}</code>,denominator: <code>\sum\limits_{k = 0}^{<strong>\mathcal{K}</strong>/2-1}{}</code>
3.3.3.1,47,denominator: <code>\sum\limits_{k = 0}^{N/2-1}{}</code>,denominator: <code>\sum\limits_{k = 0}^{<strong>\mathcal{K}</strong>/2-1}{}</code>
3.5.2.1,66,"As a rule of thumb, distributions with a skewness smaller than 2 are...", "As a rule of thumb, distributions with a skewness <strong>between -2 and 2</strong> are..."
4.3.2,76,<code>|x(i)| \leq v_{\mathrm{PPM}}(i-1)</code>,<code>|x(i)| <strong>&lt;</strong> v_{\mathrm{PPM}}(i-1)</code>
5.5.2.1,113,"Various key profile templates, normalized to a sum of 1", "Various key profile templates, normalized to a <strong>vector length</strong> of 1"
6.4,134,"Beat histogram of a piece of popular music (left) and of a string quartet performance (right)", "Beat histogram of a string quartet performance (left) and of a piece of popular music (right)"
10,169,"Here, it requires a performer or a group of performers who ``self-consciously enacts music for an audience'' \cite{sloboda85}. The performers render the composer's work", "Here, it requires a performer who ``self-consciously enacts music for an audience'' \cite{sloboda85}. The performer <strong>or a group of performers</strong> render the composer's work"
10.2.2.3,179,"has been studied by Dixon, who ...", "<strong>The regularity of the beat pulse for tempo perception of a music performance</strong> has been studied by Dixon <strong>et al.</strong>, who ..."
A.2,181,"Changing the order of operands does change the result...","Changing the order of operands does <strong>not</strong> change the result..."
B.4.1.3,195,"Blackman-Harris window $w_{\mathrm{BH}}(t)$:\\ $b_0 = 0.4243801\, b_1 = 0.4973406\, b_2 = 0.0782793$" ,"Blackman-Harris window $w_{\mathrm{BH}}(t)$:\\ <strong>$b_0 = 0.35875\, b_1 = 0.48829\, b_2 = 0.14128\, b_3 = 0.01168$</strong>"
B.4.1.4,195,"alternative Blackman window $w_{\mathrm{AB}}(t)$:\\ $\beta = 0$","alternative Blackman window $w_{\mathrm{AB}}(t)$:\\ <strong>$\beta = 4$</strong>"
[/table]</code>