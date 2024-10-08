Here  you can find the posterior chains for  Mixed Warm Dark Matter Constraints using Milky Way Satellite Galaxy Counts by Chin Yi Tan, Ariane Dekker, and Alex Drlica Wagner [(2409.18917)](https://arxiv.org/abs/2409.18917).

We run the python package emcee for 20,000 steps with 8 walkers to sample the posterior of nine free parameters in the model:
θmcmc = { Faint-end Slope (α), Luminosity scatter(σM), 50% occupation mass(M50), Occupation scatter(σgal), Baryonic effects(B), Size amplitude(A), Size scatter(σlog R),  Size power-law index(n), WDM fraction(fwdm)}

For the pure wdm chains: We have half-mode mass (Mhm) instead of WDM fraction(fwdm), which we defined as mwdm =  3 * ((10^Mhm) / 5e8)^(-3 / 10)

Also avaliable are the example notebooks where obtain a 20:1 and 10:1 posterior ratio constraints for fwdm for each MWDM mass.
