---
layout: page
title: Rubik's Cube (MIPS Assembly)
date: 2022-11-27T18:08:42-04:00
description: "1900 MIPS assembly instructions running on a SystemVerilog processor built from spit and toothpicks in COMP 541 (Digital Logic). Grade: 100%; extra credit: 4/5."
img: assets/img/rubiks_541/rubiks_541.jpg
importance: 4
toc:
    sidebar: true
giscus_comments: true
category: school
---

{% include video.html path="https://www.youtube.com/embed/CWI60TmpJHM " class="img-fluid rounded z-depth-1" center=1 %}
<div class="caption">Full demo</div>

## Description

[1900](#figures) MIPS assembly instructions running on a [SystemVerilog processor](#figures) built from spit and toothpicks in COMP 541 (Digital Logic and Computer Design).

Grade: 100%

Extra credit: 4/5

## Feedback

> Rubik’s cube simulator:
>
> Wow!
>
> Performs all moves: rotations, slices etc. Undo as well.
>
> Scrambles using PRNG. Generates 8 scrambles. User can modify them but only that last 8 are saved.
>
> Two hardwire modifications: Random number using hardware LFSR. Timer in Verilog on board — LEDs display information.
>
> Nice features: Status bar shows scrambling pattern. Easter egg — sprites change after you solve it. Accelerometer tilt makes rotations. Sound/Jingle on solve win!
>
> All in all, what a truly wonderful project. Initially I thought it would be a pretty tough one to complete, but you successfully did it. In fact, hit it out of the park! Worthy of extra credit (reported separately).
>
> — <cite>Professor Montek Singh</cite>

## Figures

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rubiks_541/541_rubiks_stats.jpg" title="Rubik's cube code stats" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">Code line count - <code>imem.mem</code> is instruction memory</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rubiks_541/541_mips_processor.jpg" title="MIPS processor implemented in SystemVerilog" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">MIPS processor implemented in SystemVerilog and deployed on Nexys A7 FPGA board</div>
