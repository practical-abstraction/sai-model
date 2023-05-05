# Socially explainable AI

Based on the STV models from [arXiv:2302.01063](https://arxiv.org/abs/2302.01063).

Three variants of models are:

1. `sai.xml` - composed of honest AI agents only
2. `sai_intr.xml` - with impersonator, who acts in-place of one of the AI agents
3. `sai_intr_fixed.xml` - with impersonator, whose strategy is fixed to never share component with quality above threshold (here, k=2)

We will used queries `sai.q` for variant (1) and a slightly modified `sai_intr.q` for (2) and (3).
