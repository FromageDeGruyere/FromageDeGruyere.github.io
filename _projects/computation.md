---
layout: page
title: Thermodynamics of computation
description: Is there a fundamental thermodynamic cost to solving a computational problem?
img: assets/img/projects/computation.png
importance: 1
category: work
related_publications: false
---

I am currently still writing this page. Feel free check out the papers below in the meantime, and try to come back at a later point.
You can also check out the following talks that were recorded:
- [YouTube Video](https://www.youtube.com/watch?v=SB2aWZkABT0) of the talk on an energy consumption advantage of quantum computation in solving Simon's problem, from the Quantum Resources Conference 2023 in Singapore.
- [YouTube Video](https://www.youtube.com/watch?v=WgWrXsTZRDk) on the thermodynamics of a fully self-contained model of quantum computation, from the Quantum Energy Workshop 2025 in Grenoble, France.


<div class="row justify-content-center">
    <div class="col-sm-6">
        {% include figure.liquid loading="eager" path="assets/img/projects/computing/dissV_setup.png" title="setup" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Thermodynamic verification of quantumness. The adversary has to solve a computational problem whose solution is then checked by the verifier. The problem should be set up in such a way that any classical adversary _provably_ has to expend an unphysical amount of energy to arrive at the correct solution, whereas a quantum adversary can in principle solve the problem with modest energy consumption.
    A correct proof with low energy consumption thus proves the quantumness of an adversary.
</div>



### Selection of relevant works

<!-- Add papers here by bib key using the nocite tag. It registers the key so it appears in the list below without showing an inline citation. -->
{% nocite meier2026quantumness meier2025energy meier2026autonomous %}

<div class="publications">
  {% bibliography --cited_in_order %}
</div>

