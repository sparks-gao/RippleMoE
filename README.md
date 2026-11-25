# RippleMoE

**A Causality-Inspired Mixture-of-Experts Framework for Multimodal Medical Diagnosis**

RippleMoE integrates medical images and clinical reports for diagnosis and supports paired, image-only, and text-only inference.

- **Ripple Routing** passes evidence between experts along a prescribed directed acyclic graph. Report evidence can guide visual experts to re-query the original image tokens and refine their states before readout.
- **Causal Contrast Buffer (CCB)** replays routing during training using a controller state from a label-compatible case in a different environment. The original diagnostic inputs and initial expert states stay fixed, so the model can learn to rely less on environment-dependent routing.

## Code release

The source code will be publicly available immediately upon acceptance of the manuscript.
