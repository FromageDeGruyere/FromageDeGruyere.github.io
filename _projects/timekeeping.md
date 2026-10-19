---
layout: page
title: Foundations of timekeeping
description: What are the ultimate precision limits for clocks set by quantum mechanics and thermodynamics? 
img: assets/img/projects/timekeeping.jpg
importance: 0
category: work
related_publications: false
---


The irreversible passage of time is an elementary part of our everyday experience, and yet we fail to understand it rigorously.
Despite this gap in human understanding of time, scientific advances have led to remarkable technological progress.
Today's state-of-the-art atomic and optical clocks keep time with a precision that would cause them to lose less than a second over the entire age of the current universe.
This raises one of the key 'pragmatic' questions in this regard: what limitations does nature impose on the possible precision of a clock? How much further can technology go?

I personally believe there is much more to clocks than this question suggests. 
Clocks prompt us to think about what time or what the passage of time really is.
While I doubt that understanding can ever be truly conclusive, I believe that there are still many lessons to be learned.
Lessons that, step by step, may eventually lead us to understand what a clock really is and how precise it can be.

### Our starting point
Pragmatically, we may say that clocks are physical systems that tell the passage of time.
This, of course, presumes there is a well-defined notion of a _passage of time_, such as the irreversible equilibration of physical systems to their thermal equilibrium.
In fact, equilibration itself, like the cooling of a cup of coffee to room temperature, can be used to tell time.
As a clock, this may not be very practical, but it nicely illustrates the variety of systems that can function as clocks.

### What is a good clock?
Good clocks are usually not based on cooling coffee; instead, they are precisely engineered systems that harness the thermodynamic flow towards equilibrium in just the right way to create a regularly ticking system (see the examples in the figure below).
How good a clock is is ultimately given by how reliably it can track the passage of time.
For the sake of simplicity, this can be quantified using two identical clocks and counting the average number of ticks it takes for their tick counts to differ by some amount, say, two ticks.


<!-- flex-grow = image width / height, so all three render at the same height -->
<div class="row">
    <div class="col" style="flex: 0.966 1 0; min-width: 0;">
        {% include figure.liquid loading="eager" path="assets/img/projects/timekeeping/3_decay_clock.png" title="decay clock" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col" style="flex: 0.459 1 0; min-width: 0;">
        {% include figure.liquid loading="eager" path="assets/img/projects/timekeeping/4_pendulum.png" title="pendulum clock" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col" style="flex: 1.380 1 0; min-width: 0;">
        {% include figure.liquid loading="eager" path="assets/img/projects/timekeeping/2_atomic_clock.png" title="atomic clock" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Everyday examples of clocks. From left to right, in increasing precision and resource cost: carbon-dating clock, pendulum clock, and an atomic clock. 
</div>

### The resource cost of timekeeping
It turns out that precision comes at a price, and a clock can not keep time arbitrarily precisely without paying for it.
The price for keeping time is non-equilibrium. 
Without that, that is, at thermal equilibrium, a clock is equally likely to tick forward as it is to tick backward.
In other words: clocks need thermodynamic irreversibility to tick (forward), and at thermal equilibrium, this ticking stops.
The story is of course more nuanced than this, and part of my work is precisely on this topic.


### What I am working on
To give an overview of the topics I have been working on (and am still working on):
- Thermodynamics of quantum and classical clocks? Is there even a fundamental difference?
- Does a clock tick when no one looks?
- Timekeeping as a special case of the quantum measurement problem.
- How do atomic clocks relate to elementary quantum clocks?

If time and clocks are fascinating topics to you as well, please do not hesitate to reach out through the email given on this [subpage]({{ '/cv/' | relative_url }}). There is also very good literature I am happy to recommend on this topic.

A talk of mine on this topic from my old days (ok, it is actually not so long ago). See this [YouTube Video](https://www.youtube.com/watch?v=IQnLb8eF--M) from the Time in Quantum Theory (TiQT) 2023 in Westport, Ireland.

### Selection of relevant works

<!-- Add papers here by bib key using the nocite tag. It registers the key so it appears in the list below without showing an inline citation. -->
{% nocite meier2025precision meier2025entropic meier2026exponential %}

<div class="publications">
  {% bibliography --cited_in_order %}
</div>

