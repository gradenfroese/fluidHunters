## Fluid hunter motivation in Central Africa: Effects on behaviour, bushmeat and income (or: hierarchical Bayes learning resource!)
<!---## :deciduous_tree: :boar::man_walking_dark_skin_tone::poultry_leg: :euro: :writing_hand_dark_skin_tone: :computer: :person_raising_hand_dark_skin_tone::cyclone:--->

<br>

This repository will host fully reproducible input data and scripts of data exploration, prior predictive checks, model notation, model fitting, model checking, and posterior predictions and plotting for the in-press paper *Fluid hunter motivation in Central Africa: Effects on behaviour, bushmeat, and income*: https://doi.org/10.1002/pan3.10502

I hope for this paper and code to be a useful resource for people (regardless of domain) looking to learn simple yet creative and flexible implementation of hierarchical Bayesian modelling. A novel aspect of this work was the weaving of the oft-disparate statistical worlds of hierarchical and structural equation modelling; we made a multivariate response generalized linear mixed piecewise structural equation model (mvGLMpwSEM). Implementation is in **brms**.

I am currently travelling and unable to push; code will be up by EOY 2023. Please do come back! And feel free to email me beforehand if curious: graden@nadagabon.org

Anonymised further data is available in the WILDMEAT database: https://wildmeat.org. You can read more about our participatory bushmeat hunting monitoring programme coupling paraecology with hunter GPS self-follows in this earlier paper: https://doi.org/10.1111/aje.12956. Shiny participatory apps in English and French, and forthcoming apps and updates are available at: https://nadagabon.org. 

<!---To run the code, download the entire repository and run scripts within the R project. The 3 scripts are as follows:

* **clean_transects.R**: this runs the diagnostic tool that corrects typos and errors in raw entered paraecologist bushmeat transect data and produces a report of its quality (see section 2.2 of the paper). If you run the script, it creates .csv products in *./outputs/cleaned/*. Similar logic not included in this repository was used cleaning the hunter self-follow data.
* **estimate_offtake.R**: this runs the algorithm used to estimate observed offtake described in section 2.3 of the paper and Appendix S3. If you run the script, it creates a .csv in *./outputs/*. 
* **summarize_offtake.R**: this runs the analyses integrating transect and self-follow data to estimate annual offtake described in section 2.3 of the paper. It further summarizes data and produces examples of figures 4--6 (different than the paper, as using the limited data). Figures 1 & 2 are excluded because their creation requires explicit spatial data; Figure 3 is a photograph. If you run the script, it creates .csv data summaries in *./outputs/* and .pdf graphics in *./outputs/figures/*.

To restore the project library locally onto your machine before running scripts (in case of issues using different package versions), begin by running the following command in the console: `renv::restore()`--->










