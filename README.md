# Constant Maturity Swap

A constant maturity swap (CMS) is an interest rate swap where floating rate equals the swap rate for a swap with a certain life (CMS tenor). For example, the floating payments on a CMS swap might be made every six months at a rate equal to the five-year swap rate.

For convexity and timing value calculation for CMS rates, Hull-White formula with correlation coefficient, between CMS rate and forward rate, set at 0.7 is used. We assume the future CMS swap rates t f has a lognormal distribution and follows geometric Brownian motion 

This swap has same payment structure as in the floating leg of CMS swap and its value is derived from the forward swap rate t f as the internal rate of return. The swap rate is calculated at the beginning of payment period. Both convexity and timing adjustment are required. 

The swap rate is calculated at the end of payment period. Only convexity adjustment is required since the swap rate is calculated and paid at the same time. Sensitivity of CMS swap pricing to LIBOR curve is available in Partial Differential Hedge (PDH) report. These sensitivities are Two-Way Delta and defined.

References:

https://zenodo.org/record/6588555/files/cmsSwap.pdf

https://zenodo.org/record/6588555#.YpE20qgpDq4

