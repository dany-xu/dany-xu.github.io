---
title: Predicting Biological Process Membership of Proteins from PPI Using LMM Model
categories:
- Project
excerpt: |
feature_text: |
  The relationship between protein and their corresponding features can resemble a mix-membership relation...
feature_image: "https://picsum.photos/2560/600?image=733"
image: "https://picsum.photos/2560/600?image=733"
---

The latent mixed membership (LMM) model has been used to predict protein functions based on the protein-protein interaction (PPI) data. Previously, the latent mixed membership model was used to predict protein functions on the MIPS dataset. However,
the overall success rate to recover the protein functions
is only around 40% to 45%. Intuitively, we believe
that this model might be more accurate in predicting
the biological process membership of proteins
from the PPI data. We implement an Estimation-
Maximization (EM) algorithm to approximate the
model to calculate the degree of membership of each
protein in each biological process group. Our result
proves a noticeable improvement in prediction accuracy
of latent mixed membership model to mixed
membership stochastic blockmodel.
{% include file.html link="/assets/posters/cmu_02510.pdf" height="600px"%}
 {% include button.html text="Poster" link="/assets/posters/cmu_02510.pdf" %}
{% include file.html link="/assets/writeups/cmu_02510.pdf"%}
{% include button.html text="Writeup" link="/assets/writeups/cmu_02510.pdf" %}
