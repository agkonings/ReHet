# ReHet
Global heterotrophic respiration estimates derived from carbon balance 

This repository contains global, gridded monthly heterotrophic respiration estimates across the period 2010-2012 obtained by inverting the land surface carbon balance. Net ecosystem productivity is obtained from CMS-Flux (Bowman et al, 2017 see http://cmsflux.jpl.nasa.gov/), gross primary productivity is obtained from scaled solar-induced fluorescence estimates from GOME-2 (Parazoo et al, 2014), and autotrophic respiration is estimated based on gross primary productivity and a spatially variable, temporally constant vegetation carbon use efficiency obtained from the C Data Model Framework - CARDAMOM (Bloom et al, 2016). The inversion provides uncertainty estimates constrained on all gross fluxes having physically meaningful signs. Sample code for the inversion is included.

For more information, please see
1.	Konings, A.G., A.A. Bloom, J. Liu, N.C. Parazoo, D.S. Schimel, and K.W. Bowman (2017): Global, Satellite-Driven Estimates of Heterotrophic Respiration
2.	Bowman, K.W. et al. (2017): Global and Brazilian carbon response to El Nino Modoki 2011-2010. In Revision.
3.	Bloom, A.A., J.F. Exbrayat, I.R. Van der Velde, L. Feng, and M. Williams (2016): The decadal state of the terrestrial carbon cycle: Global retrievals of terrestrial carbon allocation, pools, and residence times. Proceedings of the National Academy of Sciences 113(5): 1285-1290.
4.	Parazoo, N.C. et al. (2014): Terrestrial gross primary production inferred from satellite fluorescence and vegetation models. Global Change Biology 20: 3103-3121.
