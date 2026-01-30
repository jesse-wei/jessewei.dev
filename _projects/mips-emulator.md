---
layout: page
title: MIPS Emulator
date: 2023-01-10T17:45:02-04:00
description: In-use MIPS assembly emulator for simulating COMP 541 (Digital Logic) final projects at UNC. Simulates memory-mapped I/O devices, including VGA display, accelerometer, and keyboard.
img: assets/img/mips_emulator/mips_emulator.jpg
importance: 3
toc:
    sidebar: true
giscus_comments: true
category: school
---

{% include video.html path="https://www.youtube.com/embed/eTbEvDOiIdI" class="img-fluid rounded z-depth-1" center=1 %}

<div class="caption">Short (7s) demo</div>

## Link

[GitHub](https://github.com/madiali/mips-emulator)

## Description

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mips_emulator/mips_em_comp541_site.png" title="MIPS Emulator description on COMP 541 website" class="img-fluid rounded z-depth-1" center=1 %}
    </div>
</div>

Cross-platform MIPS assembly emulator for simulating [COMP 541](https://comp541.web.unc.edu) (Digital Logic and Computer Design) final projects.

Runs any MIPS program using the 32 supported MIPS assembly instructions. Simulates memory-mapped I/O devices, including VGA display, accelerometer, and keyboard.

Made in collaboration with Madison Lester over Winter break 2022. Ported from the [original MIPS emulator (C#, Windows-only)](https://github.com/jordanel/mips-emulator) made by Jordan Elliot et al.
