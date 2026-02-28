# eRO-XMM_Cross_Calibration
Tables to recreate plots from the Pilling+ 26 Paper

# M24_Comparsion
This table can be used to recreate the validation of XGA to the M24 sample.

Column descriptions:
| Column           | Description                                                         |
| ---------------- | ------------------------------------------------------------------- |
| **Cluster**      | Name of the cluster — matches the equivalent column in M24          |
| **ra**           | Right Ascension                                                     |
| **dec**          | Declination                                                         |
| **z**            | Redshift                                                            |
| **R500**         | ( r_{500} ) of the cluster (arcmin), matches the equivalent column in M24                    |
| **Nhtot**        | Hydrogen column density (1/cm²), matches the equivalent column in M24                         |
| **T_M24**        | Annulus eROSITA temperatures measured by M24 (keV)                  |
| **T_M24_hi_err** | Upper error on M24 temperature (keV)                             |
| **T_M24_lo_err** | Lower error on M24 temperature (keV)                             |
| **T_P26**        | Annulus eROSITA temperatures measured in this paper using XGA (keV) |
| **T_P26_hi_err** | Upper error on P26 temperature (keV)                             |
| **T_P26_lo_err** | Lower error on P26 temperature (keV)                             |

# DES-XCS-eRO
This table contains all the XGA and B24 measurements of the DES-XCS-eRO sample.

Column descriptions:
| Column                      | Description                                                 |
| --------------------------- | ----------------------------------------------------------- |
| **B24_NAME**                | Identical to the `NAME` column in B24                       |
| **P26_RA**                  | RA of the cluster as measured by XCS for XMM data           |
| **P26_DEC**                 | DEC of the cluster as measured by XCS for XMM data          |
| **RM_ID**                   | Identical to `mem_match_id` in the RedMaPPer catalogue      |
| **z**                       | Redshift                                                    |
| **B24_R500**                | ( r_{500} ) measured by B24 (kpc)                           |
| **LAMBDA_CHISQ**            | Richness from the RedMaPPer catalogue                       |
| **LAMBDA_CHISQ_ERR**        | Error on the richness from the RedMaPPer catalogue  |
| **B24_KT**                  | Cluster temperature from B24, equivalent to the KT column in B24  (keV) |
| **B24_KT_L**                | 1σ lower limit on B24 temperature, equivalent to the KT_L column in B24 (keV)                     |
| **B24_KT_H**                | 1σ upper limit on B24 temperature, equivalent to the KT_H column in B24 (keV)                     |
| **B24_L500_0520**           | 0.5–2.0 keV luminosity within (R_{500}) measured by B24, equivalent to the L500_0520 column in B24 (10⁴² erg s⁻¹) |
| **B24_L500_L_0520**         | Lower 1σ limit on the 0.5–2.0 keV luminosity measured by B24, equivalent to the L500_L_0520 column in B24 (10⁴² erg s⁻¹) |
| **B24_L500_H_0520**         | Upper 1σ limit on the 0.5–2.0 keV luminosity measured by B24, equivalent to the L500_H_0520 column in B24 (10⁴² erg s⁻¹)|
| **P26_T_ero**               | eROSITA temperature measured with XGA (keV)                 |
| **P26_T_ero_lo_err**        | Lower error on eROSITA temperature (keV)                    |
| **P26_T_ero_hi_err**        | Upper error on eROSITA temperature (keV)                    |
| **P26_T_xmm**               | XMM temperature measured with XGA (keV)                     |
| **P26_T_xmm_lo_err**        | Lower error on XMM temperature (keV)                        |
| **P26_T_xmm_hi_err**        | Upper error on XMM temperature (keV)                        |
| **P26_L_0.5-2_ero**         | eROSITA 0.5–2.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.5-2_ero_lo_err**  | eROSITA Lower error on 0.5–2.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.5-2_ero_hi_err**  | eROSITA Upper error on 0.5–2.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.5-2_xmm**         | XMM 0.5–2.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.5-2_xmm_lo_err**  | XMM Lower error on 0.5–2.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.5-2_xmm_hi_err**  | XMM Upper error on 0.5–2.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.1-10_ero**        | eROSITA 0.1–10.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.1-10_ero_lo_err** | eROSITA Lower error on 0.1–10.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.1-10_ero_hi_err** | eROSITA Upper error on 0.1–10.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.1-10_xmm**        | XMM 0.1–10.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.1-10_xmm_lo_err** | XMM Lower error on 0.1–10.0 keV luminosity, measured in this paper (erg s⁻¹) |
| **P26_L_0.1-10_xmm_hi_err** | XMM Upper error on 0.1–10.0 keV luminosity, measured in this paper (erg s⁻¹) |
