---
title: Ch2 Lecture 3
lecture_day: 5
readings: "2.3-2.8"
publish: true
execute: 
  cache: true
lightbox: true
filters:
    - pyodide
---

# Difference Equations

## Difference Equations



## Digital Filters


<!-- 
### Digital Signal Processing

As an introduction to the field of digital signal processing (DSP), let us reconsider the nonhomogeneous constant coefficient difference equation in a somewhat different format:

$$
\begin{equation*}
y_{k}=a_{0} x_{k}+a_{1} x_{k-1}+\cdots+a_{m} x_{k-m}, \quad k=m, m+1, m+2, \ldots, \tag{2.12}
\end{equation*}
$$

where $a_{0}$ and $a_{m}$ are nonzero. Rather than treating the $x_{k}$ 's as unknowns, view them as inputs and the resulting values $y_{k}$ as outputs. More specifically, we think of the sequence $x_{0}, x_{1}, \ldots$ as a sampling of a continuous variable such as sound in a time domain or an image in a spatial domain. In this setting we think of equation (2.12) as a linear digital filter

### Digital Filter

 of length $m$ and the resulting sequence of $y_{k}$ 's as the filtered data.![](https://cdn.mathpix.com/cropped/2024_02_16_adbe27593182d62240abg-182.jpg?height=637&width=965&top_left_y=1059&top_left_x=281)

Fig. 2.10: Graph of data from Example 2.71: Exact (-), noisy (-) and filtered (-)

As a simple example, consider a continuous function $y=f(t)$ over the domain $-1 \leq t \leq 1$. Here the variable $t$ could represent time or space. When you see a visual representation of this function (a graph of it) what you are really seeing is a discrete sampling of values of this continuous points at some resolution - a dot-to-dot so to speak.

Example 2.71. Consider the function $f(t)=\cos (\pi t),-1 \leq t \leq 1$ which defines the exact signal that we want to sample. Suppose that what we actually sample is this signal plus noise, namely the function $g(t)=\cos (\pi t)+$ $\frac{1}{5} \sin (24 \pi t)+\frac{1}{4} \cos (30 \pi t)$. Note that the signal $f(t)$ is the low frequency portion of $g(t)$ and the noise is the high frequency portion of $g(t)$. Suppose further that sampling is at the equally spaced points $t_{k}=-1+\frac{2}{64} k, k=0,1, \ldots, 64$, yielding data points $x_{k}=g\left(t_{k}\right)$. We apply the following length two filter to the data:

$$
y_{k}=\frac{1}{4} x_{k}+\frac{1}{2} x_{k-1}+\frac{1}{4} x_{k-2}, \quad k=2,3, \ldots, 64
$$

How effective is this filter in removing noise?

Solution. Rather than list the resulting numbers let's calculate and graph them. We shall interpret the number $y_{k}$ as the filtered value of the noisy $x_{k}=g\left(t_{k}\right), k=2,3, \ldots 64$ and therefore the approximation to $f\left(t_{k}\right)$ that results from this filtering. A graph of the exact data, noisy data and filtered data is given in Figure 2.10. Although it is somewhat crude (reliance on earlier values causes a slight forward shift in the filtered values), it appears to do a decent job of filtering out the noise in the sampled signal $g(t)$.

![](https://cdn.mathpix.com/cropped/2024_02_16_adbe27593182d62240abg-183.jpg?height=621&width=951&top_left_y=1004&top_left_x=283)

Fig. 2.11: Graph of data from Example 2.72: Exact (-), noisy (-) and filtered $(-)$

The filter of Example 2.71 is both causal (filtered data at a specific time only depends on samples from earlier times) and lowpass (filters out high frequency data but preserves low frequency data). -->

# Special Matrices and Transposes

# Inverse Matrices

# LU Factorization

<!-- This section should mostly be implementation. -->