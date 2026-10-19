---
layout: page
title: Equilibration and thermalization
description: (Why) do quantum systems equilibrate? How fast does this happen, and when does it fail?
img: assets/img/projects/2loa.png
importance: 1
category: work
related_publications: false
---

This topic, which originally started as a side-quest, became one of my key fascinations. So what is all the fuss about?

### Where is the problem?
Quantum mechanics (and, for that matter, classical mechanics) is time-reversal symmetric.
What this means is that if some wave function solves the Schrödinger equation, its time-reversed wave function solves the (conjugated) Schrödinger equation as well.
In different words: both forward and backward evolution are physical at the microscopic level.

In our everyday, macroscopic world, however, backward evolution often seems awkward and unphysical. Scrambled eggs do not unscramble, heat does not turn into electricity, and so on.
This is the conflict between macroscopic irreversibility and microscopic reversibility, which many people have already thought about.

### Why there may not be a problem
From a reductionist point of view, one would of course like to derive irreversibility from microscopic principles.
In its strictest form, microscopic reversibility seems at odds with this endeavor.
A very powerful perspective on resolving this problem is that macroscopic control entails ignorance.
For all practical purposes, in the macroscopic world, we do neither control nor see all microscopic degrees of freedom.
Instead, we see a coarse-grained microscopic world.
This smearing out of the many (reversible) microscopic degrees of freedom is what makes their evolution seem irreversible.


<!-- flex-grow = image width / height, so both render at the same height -->
<div class="row">
    <div class="col" style="flex: 2.186 1 0; min-width: 0;">
        {% include figure.liquid loading="eager" path="assets/img/projects/2loa/2loa_pendulum.png" title="pendulum" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col" style="flex: 0.800 1 0; min-width: 0;">
        {% include figure.liquid loading="eager" path="assets/img/projects/2loa/pendulum_many.gif" title="many pendulums" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An analogy: imagine a rod with pendulums of different lengths attached. Each pendulum behaves perfectly time reversal symmetric. Yet, if you look at their entirety through the center of mass for example, the motion looks somewhat chaotic. This is ubiquitous in nature. Coarse-graining many reversible degrees of freedom leads to an emergent seemingly irreversible motion.
</div>


### What I am working on
There are many approaches to understanding equilibration in quantum systems. 

**Isolated system equilibration:**
One standard approach is to understand equilibration as a system-subsystem phenomenon.
While the entire system may be _isolated_, meaning it is not driven and does not interact with any other system, a subsystem is not isolated anymore.
Under reasonable assumptions, the subsystem then usually equilibrates.
The exact conditions under which this happens are far from obvious and are a subject of study themselves.

**Equilibration on average:** 
It turns out, however, that when examined from the perspective of an observable, it is not only the subsystem, but often also the full isolated system that equilibrates.
Due to the unitarity of the underlying Schrödinger evolution, _true_ equilibration can of course not occur.
An initially pure state will remain eternally pure and (for finite dimensional systems) return arbitrarily closely to its initial state.
For sufficiently large systems, with the appropriate spectrum, what happens instead is the following:
expectation values of observables tend towards, and then stay close to, a _typical_ value for most of the evolution time.
Here, equilibrium is understood in a statistical sense.

**Eigenstate thermalization:** 
Thermalization is a stronger concept than equilibration.
The latter is simply about a physical system tending towards _some_ equilibrium state, whereas thermalization requires that this state be thermal.
A key concept in this context is the eigenstate thermalization hypothesis.
In simplified terms, it states that eigenstates of a Hamiltonian look thermal with respect to local observables.
As the name suggests, this is a hypothesis.
Many systems and Hamiltonians satisfy it heuristically, but rigorously proving this is often quite hard.

**Miscellaneous:**
Aside from the above approaches, I am also interested in understanding;
- Typicality. I really recommend reading the mathematical works by Vogel, Tumulka et al., for example: arXiv:[2210.10018 [quant-ph (2022)]](https://arxiv.org/abs/2210.10018) or arXiv:[2307.15624 [quant-ph] (2023)](https://arxiv.org/abs/2307.15624)
- Observable notions of entropy, and how does a second law look in isolated systems? Personal recommendation: _Unification of observational entropy with maximum entropy principles_ by Schindler, Strasberg et al. arXiv:[2503.15612 [quant-ph] (2025)](https://arxiv.org/abs/2503.15612)
- When do systems not equilibrate?
- Random matrix theory
- Non-Hermitian quantum systems and their equilibration properties

### Selection of relevant works

<!-- Add papers here by bib key using the nocite tag. It registers the key so it appears in the list below without showing an inline citation. -->
{% nocite meier2025emergence %}

<div class="publications">
  {% bibliography --cited_in_order %}
</div>

