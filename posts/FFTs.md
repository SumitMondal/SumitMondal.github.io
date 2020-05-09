---
layout: posts
title: FFTs
published: true
---

<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary">A Tale of Two FFTs</h2>
      <p><img src="/images/FFT1.gif" style="width: 35%;display: block; float:left;margin:0 1em 1em 0;"   alt="cover" /></p>
      <p> The FFT is the most useful tool in any DSP engineers toolkit. The FFT is an optimization algorithm for the <a href="https://en.wikipedia.org/wiki/Discrete_Fourier_transform">discrete fourier transform (DFT)</a>. Specifically, I implemented the Cooley-Tukey algorithm in both software and hardware.</p>
      <p> The <a href="https://github.com/SumitMondal/FFT_software">software implementation</a> was done in C++, utilizing multithreading to employ multi-core processing for the algorithm.</p>
      <p> The <a href="https://github.com/SumitMondal/FFT_hardware">hardware implementation</a> was done in VHDL, using a 10-stage pipelined architecture to implement an 8-bit FFT.</p>
      <br>
      <br>
      <br>
      <br>
      <p> Links: </p>
      <p>    <a href="https://github.com/SumitMondal/FFT_software">C++ Github</a></p>
      <p>    <a href="https://github.com/SumitMondal/FFT_hardware">VHDL Github</a></p>
      <br>
    </div>
  </div>
</div>