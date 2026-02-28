# eRO-XMM_Cross_Calibration
Tables to recreate plots from the Pilling+ 26 Paper

# M24_Comparsion
This table can be used to recreate the validation of XGA to the M24 sample.

Column descriptions:
Cluster: Name of the cluster, matches the equivalent column in M24
ra: Right Ascension
dec: Declination
z: redshift
R500: r500 of the cluster (arcmin), matches the equivalent column in M24
Nhtot: Hydrogen column density of the clusters (1/cm^2), matches the equivalent column in M24
T_M24: The annulus eROSITA temperatures measured by M24 (keV)
T_M24_hi_err: The upper error of the annulus eROSITA temperatures measured by M24 (keV)
T_M24_lo_err: The lower error of the annulus eROSITA temperatures measured by M24 (keV)
T_P26: The annulus eROSITA temperatures measured in this paper, using XGA (keV)
T_P26_hi_err: The upper error of the annulus eROSITA temperatures measured in this paper, using XGA (keV)
T_P26_lo_err: The lower error of the annulus eROSITA temperatures measured in this paper, using XGA (keV)

# DES-XCS-eRO
This table contains all the XGA and B24 measurements of the DES-XCS-eRO sample.

Column descriptions:
B24_NAME: Identical to the 'NAME' column in B24
P26_RA: Right Ascension of the cluster, as measured by XCS for XMM data
P26_DEC: Declination of the cluster, as measured by XCS for XMM data
RM_ID: Identical to the "mem_match_id" in the RedMaPPer catalogue
z: Redshift
B24_R500: r500 measured by B24 (kpc)
LAMBDA_CHISQ: The richness taken from the RedMaPPer catalogue
LAMBDA_CHISQ_ERR: The error on the richness taken from the RedMaPPer catalogue
B24_KT: The temperature of the cluster measured by B24, equivalent to the KT column in that catalogue (keV)
B24_KT_L: The 1sigma lower limit on the temperature of the cluster measured by B24, equivalent to the KT_L column in that catalogue (keV)
B24_KT_H: The 1sigma higher limit on the temperature of the cluster measured by B24, equivalent to the KT_H column in that catalogue (keV)
B24_L500_0520: 0.5-2.0keV luminosity within R500 measured by B24, equivalent to the B24_L500_0520 column in that catalogue (10**42 erg s-1)
B24_L500_L_0520: The 1sigma lower limit on the 0.5-2.0keV luminosity within R500 measured by B24, equivalent to the B24_L500_L_0520 column in that catalogue (10**42 erg s-1)
B24_L500_H_0520: The 1sigma upper limit on the 0.5-2.0keV luminosity within R500 measured by B24, equivalent to the B24_L500_H_0520 column in that catalogue (10**42 erg s-1)

