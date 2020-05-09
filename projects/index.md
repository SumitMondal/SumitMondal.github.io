---
title: About Me
layout: project
published: true
---
<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="https://github.com/SumitMondal/wormholeRouter">Wormhole NoC Router</a></h2>
      <p><img src="/images/wormhole1.jpg" style="width: 32%;display: block; float:left;margin:0 1em 1em 1em;"   alt="cover" /></p>
      <p>Multi-core processors are becoming more ubiqutous and thus there is a need for scalable, design friendly interconnection networks. I designed a 3-stage, single-cycle, Wormhole Router for network-on-chip simulations. The router uses wormhole switching techniques to buffer flits at each node to increase throughput. I created a 4x4 Mesh Network to simulate various buffer depths, injection rates, and simulation lengths.</p>
      <p>I was able to recreate nearly the exact simulation results that can be provided by Garnet 2.0, an industry standard On-Chip Network Model, but with RTL. You can read more about my design methodology and results in the <a href="/docs/wormhole.pdf">project paper</a>.</p>
      <br>
    </div>
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="https://github.com/SumitMondal/ML_AquaticMammals">Machine Learning for Marine Mammal Species Identication</a></h2>
      <p><img src="/images/dolphin_v4.jpg" style="width: 35%;display: block; float:left;margin:0 1em 1em 1em;"   alt="cover" /></p>
      <p> My team was motivated by marine researchers who use audio data to monitor the behavior of specific marine mammals. Underwater microphones are able to capture vast amounts of data that would be expensive and time-consuming for a human to manually analyze. The goal of this project is to implement a machine learning algorithm to recognize a specific marine mammal based on audio cues.</p>
      <p>A common frequency transform for audio classification is the Mel Scale which emphasizes the human hearing frequency ranges. I developed a transformation that emphasizes the frequencies that these marine mammals whistle at, which is around 5-40kHz. This transformation was inspired by the logistic function, thus I named it the Logistic Mel Scale. Checkout the <a href="/docs/ml_poster.pdf">project poster</a> for our results !</p>
      <br>
    </div>
  </div>
</div>



<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="https://github.com/SumitMondal/Edge_Detection_Basys3">Sobel Filter Implementation on Basys 3 FPGA</a></h2>
      <p><img src="/images/sobel.png" style="width: 36%;display: block; float:left;margin:0 1em 1em 1em;"   alt="cover" /></p>
      <p>Image processing, especially at higher resolutions, can be computationally intensive. An FPGA implementation of an image processing algorithm can greatly expedite runtime. I decided to implement the Sobel operator, a 3x3 convolutional filter, on the Basys 3 FPGA board using VHDL. The Sobel filter is particularly interesting because it highlights the edges of an image, as seen to the left. </p>
      <p>The input images were 640x480, and were first stored into the FPGA Block RAM, then sent through a 9-value buffer,and then the Sobel operator was performed. Finally, the output image was stored into the remaining FPGA Block RAM, and outputted to a 640x480 monitor via a VGA controller.</p>
      <br> 
    </div>
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="/docs/antenna_report.pdf">Four Patch Antenna Array</a></h2>
      <p><img src="/images/antenna_v4.png" style="width: 40%;display: block; float:left;margin:0 1em 1em 0;"   alt="cover" /></p>
      <p>The goal of this project was to design, simulate, and fabricate a directional, high gain, lightweight antenna in the 5.8 GHz band. Furthermore, the purpose of the antenna was to feed an RF energy harvesting circuit, in order to power a small motor, to move a model car. How cool is that ?! </p>
      <p> The Antenna was designed and simulated in Ansys High Frequency Structure Simulator (HFSS). Our team decided on a patch antenna due to its ease of being fabricated at the <a href="https://hive.ece.gatech.edu/">Georgia Tech Hive</a>. I was also integral to the S11 measurement and the slight adjustments needed to make the antenna have a resonant frequency at exactly 5.8 GHz. I used a spectrum analyzer, a stepper motor, and an RF signal generator to gather both the E-plane and H-plane measurements.</p> 
    </div>
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary">A Tale of Two FFTs</h2>
      <p><img src="/images/FFT1.gif" style="width: 35%;display: block; float:left;margin:0 1em 1em 0;"   alt="cover" /></p>
      <p> The FFT is the most useful tool in any DSP engineers toolkit. The FFT is an optimization algorithm for the <a href="https://en.wikipedia.org/wiki/Discrete_Fourier_transform">discrete fourier transform (DFT)</a>. Specifically, I implemented the Cooley-Tukey algorithm in both software and hardware.</p>
      <p> The <a href="https://github.com/SumitMondal/FFT_software">software implementation</a> was done in C++, utilizing multithreading to employ multi-core processing for the algorithm.</p>
      <p> The <a href="https://github.com/SumitMondal/FFT_hardware">hardware implementation</a> was done in VHDL, using a 10-stage pipelined architecture to implement an 8-bit FFT.</p>
    </div>
  </div>
</div>



<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="https://www.youtube.com/watch?v=0jGaio87u3A">The Mandelbrot Set</a></h2>
      <p><img src="/images/mandelbrot.png" style="width: 38%;display: block; float:left;margin:0 1em 1em 0;"   alt="cover" /></p>
      <p>The mandelbrot set is a set of complex numbers that does not diverge when iterated starting from zero.</p>
      <p>Images of the mandelbrot set have exquisite and infinitely complicated edges. The mandelbrot is a fractal meaning that there is no definite length to the boundary of the specific mandelbrot.</p>
      <p> The image to the left shows one of the mandelbrot sets that I generated using C++ and OpenGL. </p>
    </div>
  </div>
</div>


<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="/docs/blimp_poster.pdf">Blimp My Ride (Capstone Design Project)</a></h2>
      <p><img src="/images/blimp.JPG" style="width: 40%;display: block; float:left;margin:0 1em 1em 0;"   alt="cover" /></p>
      <p>For my Senior Design Capstone project, a team of engineers and I designed a Robotic Blimp Guide. The idea was to create a robotic guide to navigate users through a large unknown environment such as a museum, stadium, or convention center.</p>
      <p> Why choose a blimp you might ask? Quadcopters are dangerous in populated environments and a wheeled robot is unable to climb stairs or avoid people as easily as a floating blimp ! </p>
      <p> The robotic blimp has an onboard camera that our team used to implement a computer vision algorithm to recognize <a href="https://april.eecs.umich.edu/software/apriltag">April Tags</a>. The robotic blimp uses the april tags to traverse the environment. I was the lead designer of the proportial-integral-derivative <a href="https://en.wikipedia.org/wiki/PID_controller">(PID) controller</a>, which is the main code that drives the robots motors towards the user-defined location.</p>
    </div>
  </div>
</div>


<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary"><a href="https://www.youtube.com/watch?v=9ShZ0jGuPjY">Smart Mirror Assistant</a></h2>
      <p><img src="/images/mirror.png" style="width: 25%;display: block; float:left;margin:0 1em 1em 0;"   alt="cover" /></p>
      <p>For my embedded systems final design project, a team of my peers and myself created a smart mirror. A smart mirror is a screen with a 1 way mirror overlayed, such that the screen can be used as a mirror with a background display for various accessorized information. The information was displayed and controlled by a Raspberry Pi 3.</p>
      <p>Some of the features that our smart mirror implements includes: weather, date, google calendar, google assistant, and google maps traffic. Look good feel good !</p>
    </div>
  </div>
</div>