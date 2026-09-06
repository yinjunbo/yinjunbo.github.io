---
layout: page
title: Verifiable design by agents
description: Fixing what counts as success before trusting a design.
img: assets/img/research/agentic-science.png
importance: 2
category: work
---
<div class="row justify-content-sm-center mt-3 mb-4">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/research/agentic-science.png" class="img-fluid rounded" %}
  </div>
</div>

**The problem.** Generation is cheap and verification is expensive. A model can propose ten thousand binders in an afternoon; a wet lab can test a handful in a month. The bottleneck in AI-driven discovery is no longer sampling, it is deciding which candidates deserve that month — and being able to justify the decision afterwards.

**What I build.** Pipelines in which an autonomous agent searches design strategies under an explicit *task contract*: a machine-checkable statement, fixed in advance, of what would count as success and what evidence is required to claim it. The agent selects and composes tools, runs the checks, and produces both a design and the audit trail behind it. Because the acceptance criteria are frozen before the search begins, results are reproducible and failures are attributable to a specific unmet condition rather than to model taste. This line is supported by a KAUST Competitive Research Grant on AI agents for protein design, on which I am a co-investigator.

**Where it is going.** Toward closed loops: contracts that are refined by experimental outcomes, so that each round of wet-lab feedback tightens what the next round of designs must satisfy. Protein binder design is the proving ground; the machinery is not specific to proteins.
