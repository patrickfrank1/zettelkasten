# Be good argument driven, not data driven

url: <https://twitchard.github.io/posts/2022-08-26-metrics-schmetrics.html> \
tags: data driven, data science trends, reasoning with data, decision making

- current trend: everything is data and metrics driven
- problems with that approach
  - favour bad arguments that involve data over good arguments that don't
  - insist on metrics in realms where they can't be the foundation of a good argument

When to be data driven?

1. all factors that drive your metric are well understood: measure outcomes and compare against the counterfactual
2. you can run experiments: do some attribution with A/B testing, multi armed bandits, etc.
3. are you prepared to do some very very fancy statistics?
    - hairier the further away from a controlled experiment
    - can try to make conclusions from field data
    - distinguish between correlation and causation; causal inference

**Otherwise don't**, current general sentiment: metrics are useful in the common case and in the exceptional case measurement is inappropriate; but the exact opposite is actually true (more often than not analysis is riddled by selection bias, hidden variable interactions, etc.)

What can go wrong being too data driven?

1. suspension of disbelief: metrics are important to your organization, so you introduce them and forget that they are meaningless
2. streetlight effect: focus disproportionately on small improvements that can be measured and suspend more nuanced, meaningful but harder to measure improvements
3. cost morale, destroy motivation, encourage growth hacking away
4. sign of weak leadership: use metrics as a crutch to make uncomfortable decisions
