# ADMM_Quadratic

This is a project to use ADMM to solve the following problem in Python

$$\text{min}_{x \in \mathbb{R}^n} \frac{1}{2} x^T P x + q^T x + r$$
   
   Subject to $ lb \leq x \leq ub $

   where $ P \in S_+ $, $b \in \mathbb{R}^n $,  $r $ is a constant, and $ l $ and $ u $ are scaling parameters.