# ResultsSamplingConcentrationsParameters
Repository of results obtained after the sampling of concentrations and parameters
Here saved are 4000 randomly chosen values out of 1e+06 sampled sets. 
Saved are the results for the model using automatically assigned convenience kinetic and the specific mechanistic kinetics of the anaerobic metabolic model of E coli. 

Concentrations were sampled between [0.01 10] umol/gdw  <br />
Alphas (=S/km) were sampled between [0.01 100] 
 
 The results are stored in .mat files. Following the description of the acronyms: 
 
      - DG0 = gibbs free energy of reaction; 
      - keq = equilibrium constants; 
      - Nf  = stoichiometic matrix; 
      - R   = reactions names;
      - S   = species names;
      - sve_cnc    = feasible sampled concentrations (iterations x m);
      - sve_prm    = all sampled parameters (stable and unstable sets) (iterations x #parameters);
      - sve_RedJac = Jacobian matrices (m x m x iterations)
      - sve_MaxRelEig = value of the maximum real eigenvalue (1 x iterations);
      - sve_CJ     = flux control coefficients (n x n x stable_models);
      - sve_CS     = concentration control coefficients (m x n x stable_models);
      - sve_Elas   = elasticity matrices (n x m x stable_models);
      
      


