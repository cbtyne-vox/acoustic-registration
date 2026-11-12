# Acoustic Registration Lab

A browser-based tool for teaching acoustic registration in voice pedagogy, made by Chadley Ballantyne, Stetson University. The reverse of the Vowel Synth Lab: instead of setting fR1 and hearing the result, you sing, and the lab measures fR1 in your own voice and shows whether you are in an open, close or whoop timbre.

- Live readout of the sung pitch, fR1, fR1 ÷ fo (ripples per cycle) and H2, with the label open, close, whoop or H1 above fR1, using the same rule as the Vowel Synth Lab
- Grand staff and piano keyboard showing your harmonics and where fR1 sits
- A 30-second trail, so you can sing a scale and watch H2 and H1 cross fR1
- Ripple view: your sound filtered to show fR1 ringing after each glottal closure, plus the glottal flow with the resonances removed
- Microphone or audio file input

fR1 is measured with closed-phase covariance analysis, the same method as the Inverse Filter Lab's Auto estimate. It is reliable up to about B4 on a steady note. Above about C5 the harmonics are too far apart to find fR1, and the page says so.

Open `index.html` in Chrome or Safari, or visit the live page through GitHub Pages, and allow the microphone when asked.
