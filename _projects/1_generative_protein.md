---
published: false # 暂时下线，日后大改后再打开
layout: page
title: Generative protein design
description: Turning a functional specification into a molecule a model can actually produce.
img: assets/img/research/generative-protein.png
importance: 1
category: work
related_publications: true
---
<div class="row justify-content-sm-center mt-3 mb-4">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/research/generative-protein.png" class="img-fluid rounded" %}
  </div>
</div>

**The problem.** Protein generative models can produce plausible sequences, but a scientist rarely wants "a plausible protein" — they want one that catalyses a particular reaction, binds a particular target, or carries a particular motif in a particular place. The gap is a language: how do you state a functional requirement in terms a model can condition on?

**What I build.** Generative models that accept combinations of functional annotations as conditions rather than a single label. {% cite yin2025cfpgen %} introduces combinatorial functional protein generation with diffusion language models, conditioning jointly on enzyme-commission numbers, GO terms and motifs so that multiple functional constraints can be imposed at once. {% cite feng2026segdesign %} makes the same idea modular at the segment level, so that individual regions of a protein can be re-engineered while the rest is held fixed. {% cite guo2025nspep %} extends design beyond the twenty canonical residues to peptides containing non-standard amino acids, which is where much of the therapeutic space actually lives.

**Where it is going.** Function is currently specified by whatever annotation vocabularies happen to exist. The next step is learning the specification language itself, so that a design goal can be stated the way a biologist would state it and still be executable by a model.
