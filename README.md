# 1DIsingModel
Code for simulating 1D Ising Model 

1. Run ising_1D to define true model, parameters, and observables


2. Run diffusion_ising for the Simple MLP // training
  --> Defined parameters in this section
   - Uses standard noise prediction, MLE Loss
   - Uses reverse time Euler sampling

3. Run plot_correlations to visualize xi v. T, domain wall density v. T
  - Outputs two visuals: correlation length xi and domain wall density based on xi and rho data from diffusion_ising script

4. plot_diffusion_v_true_1D
  - loads true ising data and diffusion results to plot the domain wall density vs. temperature for both the true and generated 1D ising
