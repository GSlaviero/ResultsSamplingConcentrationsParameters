# ResultsSamplingConcentrationsParameters
Repository of results obtained after the sampling of concentrations and parameters
Here saved are 2000 randomly chosen values out of 1e+06 sampled sets. 
Saved are the results for the model using automatically assigned convenience kinetic and the specific mechanistic kinetics of the anaerobic metabolic model of E coli. 

 The results are stored in .mat files. Following the description of the acronyms: 
      - SCN = feasible sampled concentrations (iterations x m);
      - DG0 and keq;
      - R = reactions names;
      - S = species names;
      - Fluxes = steady state fluxes;
      - spl_parameters = all sampled parameters (stable and unstable sets) (iterations x #parameters);
      - CJ_rec = flux control coefficients (n x n x stable_models);
      - CS_rec = concentration control coefficients (m x n x stable_models);
      - E_rec  = elasticity matrices (n x m x stable_models);
      - eigenvalues_full = all eigenvalues (n x iterations);
      - MaxRealEigens = value of the maximum real eigenvalue (1 x iterations);
