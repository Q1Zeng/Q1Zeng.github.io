---
layout: page
title: Competitive Physics Informed Neural Network (CPINN)
description: "A generative-discriminator framework for Physics Informed Neural Networks (PINN). Advised by Florian Schäfer and Spencer Bryngelson, joint work with Yash Kothari. Accepted for the 11th International Conference on Learning Representations Interational."
img: assets/img/CPINN_ICLR_thumbnail.png
importance: 1
category: "Research"
---
<!-- 
Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->
<!-- # Translating ERDDAP Into Different Languages -->
<!-- ## Overview -->
## Abstract
Neural networks can be trained to solve partial differential equations (PDEs) by using the PDE residual as the loss function. This strategy is called "physics-informed neural networks" (PINNs), but it currently cannot produce high-accuracy solutions, typically attaining about 0.1% relative error. We present an adversarial approach that overcomes this limitation, which we call competitive PINNs (CPINNs). CPINNs train a discriminator that is rewarded for predicting mistakes the PINN makes. The discriminator and PINN participate in a zero-sum game with the exact PDE solution as an optimal strategy. This approach avoids squaring the large condition numbers of PDE discretizations, which is the likely reason for failures of previous attempts to decrease PINN errors even on benign problems. Numerical experiments on a Poisson problem show that CPINNs achieve errors four orders of magnitude smaller than the best-performing PINN. We observe relative errors on the order of single-precision accuracy, consistently decreasing with each epoch. To the authors' knowledge, this is the first time this level of accuracy and convergence behavior has been achieved. Additional experiments on the nonlinear Schrödinger, Burgers', and Allen-Cahn equation show that the benefits of CPINNs are not limited to linear problems.

Preprint avaliable at [arxiv](https://arxiv.org/abs/2204.11144).