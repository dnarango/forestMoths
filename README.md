# forestMoths

README: Data from: Tree Composition Mitigates the Negative Effects of Urbanization on Specialist and Generalist Forest Moth Communities

R script, JAGS model, and data used to test relationships between moth community metrics, urbanization and forest characteristics in Delaware and Pennsylvania, USA.

Description of the data and file structure
File 1: JAGS_moth_analysis.txt- JAGS model used to test relationships between moth community metrics, urbanization, and forest characteristics. Read from X.

File 2: JAGS_moth_specializationDistance_analysis.txt- JAGS model used to test relationships between moth specialization distance, urbanization, and forest characteristics. Read from X.

File 3: JAGS_moth_richness_rarefied.txt- JAGS model used to test relationships between moth rarefied richness, urbanization, and forest characteristics. Read from X.

File 4: moth_bayesian_analysis.R-Loads datasets and formats data, and runs JAGS models.

File 5: moth_data.csv-plot level abundance, biomass, and richness for specialists and generalists

File 6: site_summary.csv - site-level summaries of moth abundance, moth biomass, impervious surface, basal area, genus richness and Lepidoptera-rich tree basal area.

File 7: allmoths_traits_12feb2024_format.csv - Individual species and counts for each sampling event with associated traits.

File 8: moth_rareifiedRichness_specialists.csv - Rarefied richness of genus specialist moths

File 9: moth_rareifiedRichness_generalists.csv - Rarefied richness of genus generalist moths

File 10. leps_withplants.csv moth species, counts, and basal area of host trees at each plot

File 11. final_foodplant_analysis.Rmd GLMM of Host plant relationships with the abundance of individual species.

File 12. rlq_data.RDS matrices for RLQ and Fourth Corner Analysis

File 13. rlq_data_justHerbivores.RDS matrices for RLQ and Fourth Corner Analysis
