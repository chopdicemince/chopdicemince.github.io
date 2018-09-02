---
layout: post
title: compressed sensing
date: 2018-09-02
---

# Who is Harry Nyquist?

[Harry Nyquist](https://www.electronicdesign.com/digital-ics/harry-nyquist-founding-father-digital-communications) lived from 1889 to 1976. He was born in Sweden. He moved to the U.S., studied electrical engineering, and worked at AT&T (American Telephone & Telegraph).

# What is the "Nyquist rate" or "Nyquist frequency?"

In 1928, Nyquist published his most famous paper: [Certain Topics in Telegraph Transmission Theory](https://monoskop.org/images/2/2e/Nyquist_Harry_1928_Certain_Topics_in_Telegraph_Transmission_Theory.pdf). 

[Harry Nyquist: A Founding Father Of Digital Communications](https://www.electronicdesign.com/digital-ics/harry-nyquist-founding-father-digital-communications) describes the Nyquist Sampling Theorem as follows:

> According to the Sampling Theorem, an analog signal must be sampled at regular intervals over time and at twice the frequency of its highest-frequency component to be converted into an adequate representation of the signal in digital form. Thus, the "Nyquist frequency" is the highest frequency that can be accurately sampled. It represents one-half of the sampling frequency. Adhering to the Nyquist Sampling Theorem ensures no lost data upon reconstruction in the analog domain.

# What is a sparse signal?

A signal is __sparse__ if it has "very few" nonzero coefficients (when it is represented in some basis).

Sparse approximations are used in the image format JPEG (Joint Photographic Experts Group), and in the video formats MPEG (Moving Picture Experts Group), which includes [MP3](https://www.loc.gov/preservation/digital/formats/fdd/fdd000012.shtml).

# What is compressed sensing?

Compressed sensing is a field of study which tries to simplify sparse signals---for example, by decreasing the number of samples.

The ideas of compressed sensing have been around for a long time, since 1795 or earlier.

Rather than sampling a signal at specified times, compressed sensing algorithms usually compute inner products between the signal and certain test functions---often, these test functions are created with some randomness.

# Have people used compressed sensing in real-world applications?

Yes, people have used compressed sensing in real-world applications.

For example, see [Improved Pediatric MR Imaging with Compressed Sensing](https://pubs.rsna.org/doi/10.1148/radiol.10091218). The begining of the paper has the following short conclusion:

> A combination of parallel imaging and compressed sensing is feasible in a clinical setting and may provide higher resolution and/or faster imaging, addressing the challenge of delineating anatomic structures in pediatric MR imaging.

# What math topics does compressed sensing use?

Compressed sensing uses the following math topics:

* Vector spaces (inner products).
* Real analysis (p-norms).
* Linear algebra (matrices).
* Optimization (nonlinear, minimization, convexity).
