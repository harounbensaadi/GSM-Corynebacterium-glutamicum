[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/harounbensaadi/GSM-Corynebacterium-glutamicum/HEAD)
### Assignment - Computer-aided Cell Factory Design (27410 ) 
# Application of Genome Scale Modeling for L-lysine production through _Corynebacterium glutamicum_
Course responsible: Dr. Igor Marín de Mas

## Project summary: 

L-lysine is an essential amino acid used as an ingredient in both the food industry to ensure nutrially levels, and the cosmetics industry. The current state-of-the-art on its production is a Fermentation-based biomanufacturing employing the bacterium _Corynebacterium glutamicum_ and glucose as a feedstock.   

The aim of the project is to use Genome Scale Models (GEMs) in order to guide the improvement of L-lysine production. Two GSMs models for _C. glutamicum_ were identified and used throughout this work: iCGB21R (2021) and iCW773 (2017). An analysis was performed regarding the effects of swtching the carbon soruce in the media. Furthermore, the ratinal engineering done in a influential paper in metabolic engineering was tried to be reproduced in iCGB21R. Finally, it is also explored, throught manual gene knokout. Moreover, it is also implemented a pipeline to facilitate working with the model, annotating the genes with their common name instead of the, cryprtic code used in the original iCGB21FR. 

Overall, it has been interesting to use and apply GSM for simulating in-silico the strategies that could be used to improve the L-lysine production and its cell factory. Thus, representing an alternative approach to laboratory experiments. 

## Project overview

The main Jupyter Notebooks provided for this assignement are:
- theoretical_yield.ipynb  
- adding_lysine_export_reaction.ipynb  
- gene_annotation.ipynb 
- gene_essentiality.ipynb
- main_script.ipynb  
- manual_gene_knockout.ipynb  
- medium_optimization.ipynb  
- memote_anaconda.ipynb
- model.ipynb  
- optgene.ipynb
- optknock.ipynb
- paper_replication.ipynb
- report.ipynb

Additionaly, a requirements.txt file was automatically generated and it lists the main Python packages essential for running this code.

It should be noted that a detailed explanation of performed analysis can be found in **report.ipynb**
