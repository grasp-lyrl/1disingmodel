# 1D Ising Model
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

# 2D Ising Model 

1. 2D_MC_Initialization
  - Initialize 2D monte carlo

2. 2D_diffusion_utils
  - Define utilities needed for diffusion model

3. 2D_Model
  - UNet, attention, and diffusion classes

4. 2D_Training
  - Train model
    --> 100 Epochs 
    --> 300 timesteps

5. 2D_sampling
  - Draw samples

6. 2D_JS_Div
  - JS Divergence

7. 2D_Loop
  - Iterate through temps
