# CS Applications of the Discrete Fourier Transformation

This repository contains two iPython notebooks (based on SageMath
7.5.1), showing two applications of the _Discrete Fast Fourier
Transformation_.


## DTMF tone recognition

DTMF tones, the distinct sounds associated with a certain number
on most telephone keyboards can be identified from a continuous audio
stream using the Fourier Transformation. This is how a telephone computer
might work.
[➡️ View Notebook](https://github.com/v4lli/fourier/blob/master/dtmf.ipynb)

## Lossy JPEG compression\*

The original JPEG standard uses the _Discrete Cosine Transformation_
(very similar to the DFT). This notebook shows what's at least
necessary to lossfully compress an example image. The notebook shows
how different compression ratios affect file size and image quality.

[➡️ View Notebook](https://github.com/v4lli/fourier/blob/master/GhettoJPEG.ipynb)

\* Not actually DFFT, but the _discrete cosine transformation_, which
is very similar.

_Note: The example image (commonly known as Lena, called Lisa.png in the notebook) is *not* MIT-licensed. See
https://en.wikipedia.org/wiki/Lenna_
