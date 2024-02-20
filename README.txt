README: Data from: Tree Composition Mitigates the Negative Effects of Urbanization on Specialist and Generalist Forest Moth Communities

R script, JAGS model, and data used to test relationships between moth community metrics, urbanization and forest characteristics in Delaware and Pennsylvania, USA.

Description of the data and file structure
File 1: JAGS_moth_analysis.txt- JAGS model used to test relationships between moth community metrics, urbanization, and forest characteristics. Read from X.

File 2: JAGS_moth_specializationDistance_analysis.txt- JAGS model used to test relationships between moth specialization distance, urbanization, and forest characteristics. Read from X.

File 3: JAGS_moth_richness_rarefied.txt- JAGS model used to test relationships between moth rarefied richness, urbanization, and forest characteristics. Read from X.

File 4: moth_bayesian_analysis.R-Loads datasets and formats data for the JAGS model. Has code for summarizing and visualizing posterior distributions.

File 5: site_summary.csv - site-level summaries of moth abundance, moth biomass, impervious surface, basal area, genus richness and Lepidoptera-rich tree basal area.

File 6: allmoths_traits_12feb2024_format.csv - Individual species and counts for each sampling event with associated traits.

File 7: moth_rareifiedRichness_specialists.csv - Rarefied richness of genus specialist moths

File 8: moth_rareifiedRichness_generalists.csv - Rarefied richness of genus generalist moths

File 9. leps_withplants.csv moth species, counts, and basal area of host trees at each plot

File 10. final_foodplant_analysis.Rmd GLMM of Host plant relationships with the abundance of individual species.

File 11. rlq_data.RDS matrices for RLQ and Fourth Corner Analysis

File 12. rlq_data_justHerbivores.RDS matrices for RLQ and Fourth Corner Analysis