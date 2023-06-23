# EPA1361 Model Based Decision Making
## Group 9: Gelderland Analysts
Authors:
- Arthur Ronner
- Robin Vrijhoeven
- Eline Slaats
- Marie-Anne de Gier
- Lucas Nijhof
- Lars van Koetsveld van Ankeren

### Final policy notebook
To reproduce the results from our project, run final_policy.ipynb. 
The repository includes the results from previous runs, that were used to generate the graphs in the report. The notebook automatically loads these from the following three data files: 1024_sen_SOBOL_np2.tar.gz; re-evaluation.tar.gz and Base_scenario_pf2.tar.gz.  
If you would like to generate new results, please uncomment the lines saving new outcomes to these files.  
  
The repository includes our custom version of the dike model and problem formulation. They are imported automatically in the notebook, therefore running only the notebook is sufficient to reproduce our results.  

### Requirements
All imports are included in the first cell of the notebook. It requires the following external packages:
- Numpy 
- Pandas
- Matplotlib.pyplot
- Seaborn 
- EMA_workbench
- SALib.analyze
