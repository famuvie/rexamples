# Worked R examples

## Mixed effect models

These are all the mixed effect model examples from two chapters of my book
[Extending the Linear Model with R](https://julianfaraway.github.io/faraway/ELM/).
Each model is fit using several different methods:

- [lme4](https://github.com/lme4/lme4)
- [INLA](https://www.r-inla.org/)
- [STAN](https://mc-stan.org/)
- [BRMS](https://paul-buerkner.github.io/brms/)
- [MGCV](https://www.maths.ed.ac.uk/~swood34/mgcv/)

I have focused on the computation rather than the interpretation
of the models.

### Examples

- [Single Random Effect](mixed/pulp.md) - the `pulp` data
- [Randomized Block Design](mixed/penicillin.md) - the `penicillin` data
- [Split Plot Design](mixed/irrigation.md) - the `irrigation` data
- [Nested Effects](mixed/eggs.md) - the `eggs` data
- [Crossed Effects](mixed/abrasion/md) - the `abrasion` data
- [Multilevel Models](mixed/jspmultilevel.md) - the `jsp` data
- [Longitudinal Models](mixed/longitudinal.md) - the `psid` data
- [Repeated Measures](mixed/repeated.md) - the `vision` data
- [Multiple Response Models](mixed/jspmultiple.md) - the `jsp` data
