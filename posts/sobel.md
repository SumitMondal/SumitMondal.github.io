---
layout: posts
title: sobel
published: true
---

<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary">Sobel Filter Implementation on Basys 3 FPGA</h2>
      <p><img src="/images/sobel.png" style="width: 36%;display: block; float:left;margin:0 1em 1em 1em;"   alt="cover" /></p>
      <p>Image processing, especially at higher resolutions, can be computationally intensive. An FPGA implementation of an image processing algorithm can greatly expedite runtime. I decided to implement the Sobel operator, a 3x3 convolutional filter, on the Basys 3 FPGA board using VHDL. The Sobel filter is particularly interesting because it highlights the edges of an image, as seen to the left. </p>
      <p>The input images were 640x480, and were first stored into the FPGA Block RAM, then sent through a 9-value buffer,and then the Sobel operator was performed. Finally, the output image was stored into the remaining FPGA Block RAM, and outputted to a 640x480 monitor via a VGA controller.</p>
      <br>
      <p> Links: </p>
      <p><a href="https://github.com/SumitMondal/Edge_Detection_Basys3">Github</a></p>
      <p>    <a href="/docs/sobel_paper.pdf">Design Report</a></p>
      <br> 
    </div>
  </div>
</div>