My research into variational inference and score matching as part of the 2024 Physics DRP.

Takeaways:
- I learned about *generative modelling* -- you have samples from distribution $D$ and want to learn a model that lets you sample from $D$
- Variational inference provides a learnable objective, using latent variables and minimizing KL-divergence
- Score matching (more recent) provides a learnable objective of matching [gradient of log-liklihood]

My final presentation slides are `presentation.pdf`, and code is in `score-matching.ipynb`.

Note: I scrambled to code up NCSN at the end, so the samples I obtained are bad probably because my model is bad (incorrect and/or poorly tuned).
