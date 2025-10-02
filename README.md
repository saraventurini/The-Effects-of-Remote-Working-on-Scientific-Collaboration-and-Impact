# The-Impact-of-Remote-Working-on-Academic-Production
Repository for the code and analysis in the paper “The Impact of Remote Working on Academic Production” by Sara Venturini, Satyaki Sikdar, Martina Mazzarello, Francesco Rinaldi, Francesco Tudisco, Paolo Santi, Santo Fortunato, Carlo Ratti.

Data
- `https://github.com/satyakisikdar/openalex`: GitHub page  contains the instructions to create the snapshots from OpenAlex.
- `0.Tables.ipynb`: Jupyter notebook to create, clean, and save the data files used in the analysis. Details are reported in the Methods chapter of the paper.

Analysis
- `1.TeamDistanceAnalysis.ipynb`: Jupyter notebook to calculate the fraction of inter/inter-institutions collaborations and the Average Team Distance.
- `2.Model-info.ipynb`: Jupyter notebook to create, clean, and save  the data files used in the application of the model. 
- `3.Model_edges-2authors.ipynb`: Jupyter notebook to perform the model with pairwise interactions on works with 2 authors. 
- `4.Model_edges-allworks.ipynb`: Jupyter notebook to perform the model with pairwise interactions on all the works. 
- `5.Model_triangles-3authors.ipynb`: Jupyter notebook to perform the model with hyperedges on works with 3 authors. 
- `6.ImpactFactor-IF.ipynb`:  Jupyter notebook to calculate the Impact Factor. 
- `7.Relations-metrics.ipynb`: Jupyter notebook to calculate the relations between the Impact Factor and the Average Team Distance.
- `8.OnlinePlatformsData.ipynb`: Jupyter notebook to plot daily and monthly active users on Microsoft Teams from July 2019 to October 2023, based on public earnings reports.
