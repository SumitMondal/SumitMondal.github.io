---
layout: posts
title: wormhole
published: true
---

<div class="container">
  <div class="row">
    <div class="col">
      <br>
      <h2 class="text-secondary">Wormhole NoC Router</h2>
      <p><img src="/images/wormhole1.jpg" style="width: 32%;display: block; float:left;margin:0 1em 1em 1em;"   alt="cover" /></p>
      <p>Multi-core processors are becoming more ubiqutous and thus there is a need for scalable, design friendly interconnection networks. I designed a 3-stage, single-cycle Wormhole Router for network-on-chip simulations. The router uses wormhole switching techniques to buffer flits at each node to increase throughput. I created a 4x4 Mesh Network to simulate various buffer depths, injection rates, and simulation lengths.</p>
      <p>I was able to recreate nearly the exact simulation results that can be provided by Garnet 2.0, an industry standard On-Chip Network Model, but with RTL. You can read more about my design methodology and results in the paper.</p>
      <br>
      <br>
      <p> Links: </p>
      <p>    <a href="https://github.com/SumitMondal/wormholeRouter">Github</a></p>
      <p>    <a href="/docs/wormhole.pdf">Design Report</a></p>
      <br>
    </div>
  </div>
</div>