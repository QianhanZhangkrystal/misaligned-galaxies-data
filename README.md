# misaligned-galaxies-data
This repository contains two CSV files of 37 misaligned galaxies as our sample (misalign_final_publish) and 37 aligned galaxies (control_final_publish) as control sample of our work, we list some properties from MaNGA and HI-MaNGA of these galaxies here. The definitions of these parameters are as follows：
1. PLTAEIFU:PLATE-IFU designation of MaNGA observation
2. Re_kpc(kpc): The effective radius of luminosity of a galaxy measured in kpc.
3. SNR_HI: The signal-to-noise ratio of the HI spectrum calculated through the function mentioned in the paper.
4. kappa: Spectral shape parameter K calculated through curve of growth method, where K>0 indicating a single-peaked shape and K<0 indicating a double-horned shape.
5. kappa_statErr: The standard error of kappa.
6. af: Spectral asymmetry parameter A_F calculated through curve of growth method, where the larger A_F is means a more asymmetric HI profile.
7. af_statErr: The standard error of af.
8. cv: The concentration of HI profile calculated as C_V = V_85/_V25, where V_85 and V_25 are the velocity widths containing 85% and 25% of the flux of HI profile.
9. cv_statErr: The standard error of cv.
10. Dn4000: Global 4000AA break calculated in 1.5Re of a galaxy from MaNGA DAP.
11. M_all(M_sun): The logarithm of the stellar mass of the galaxy to the base 10 from MaNGA DRP.
12. class_mis(or class_con): The classification of the galaxy using stellar mass and Dn4000 mentioned in the paper, including star-forming (SF) and quiescent (QS) sequence.
13. inclination: The inclination angle of the galaxy calculated through the function mentioned in the paper.
14. OBJRA(deg): Right ascension of the galaxy from MaNGA DAP.
15. OBJDEC(deg): Declination of the galaxy from MaNGA DAP.
16. nsa_iauname: IAU name of the galaxy from NSA catalog.
17. Z: Redshift of the galaxy from MaNGA DAP.
18. VOPT(km/s): Optical velocity from HI-MaNGA - used to set centre frequency of radio observation in km/s.
19. SESSION: GBT program session during which target was observed. In format AA-BB-CC (e.g. if observed in three sessions), where AA, BB, CC are the session IDs. Set to "ALFALFA" if data from ALFALFA survey.
20. PEAK(mJy): The peak HI flux density in mJy.
21. FHI(Jy km/s): The integrated flux of the HI line.
22. EFHI(Jy km/s): Uncertainty on the integrated flux of the HI line.
23. LOGMHI(M_sun): Log of the HI mass (in solar masses) assuming D = vopt/70 Mpc/km/s.
24. VHI(km/s): Centroid of the HI line detection.
25. EV(km/s): Uncertainty on VHI.
26. W50(km/s): Width of the HI line measured at 50% of the peak of the HI line.
27. conflag: Flag indicating whether the profile measurements may be unreliable due to multiple galaxies within the beam and at similar redshift (Set to 1 if likely confused, otherwise 0).
28. conf_prob: Probability that more than 20% of integrated flux is from galaxies other than primary target.
