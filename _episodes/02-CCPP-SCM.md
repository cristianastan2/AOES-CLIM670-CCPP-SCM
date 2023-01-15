---
title: "CCPP-SCM"
teaching: 0
exercises: 0
questions:
- "What is a single column model?"
objectives:
- "Learn about the Common Community Physics Package - Single Column Model"
---
### What is a single column model?
- A single column model (SCM) can be a valuable tool for diagnosing the performance of a physics suite, from validating that schemes have been integrated into a suite correctly to deep dives into how physical processes are being represented by the approximating code. 
- This SCM has the advantage of working with the Common Community Physics Package (CCPP), a library of physical parameterizations for atmospheric numerical models and the associated framework for connecting potentially any atmospheric model to physics suites constructed from its member parameterizations. In fact, this SCM serves as perhaps the simplest example for using the CCPP and its framework in an atmospheric model.
- The SCM code calls CCPP-compliant physics schemes through the CCPP framework code. As such, it requires the CCPP framework code and physics code, both of which are included as submodules within the SCM code. This package can be considered a simple example for an atmospheric model to interact with physics through the CCPP.

### CCPP-SCM Overview
![](../files/scm_1slide.pdf)
