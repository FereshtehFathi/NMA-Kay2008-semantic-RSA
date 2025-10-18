
🧠 Scripts for Semantic RSA Project
This folder contains Jupyter notebooks and helper scripts used for visualizing and summarizing Representational Similarity Analysis (RSA) results from the Kay et al. (2008) dataset.
📄 Files
rsa_visualization.ipynb
Generates visual plots from the RSA results. 
Inputs: rsa_basic.csv, rsa_perm_bootstrap.csv (from /results/)
Outputs: Scatterplots per ROI and a summary bar plot (saved in /figures/)
Uses: matplotlib, seaborn, pandas
🎯 Purpose
These scripts make the RSA results easier to interpret and ready for presentation or publication.
They visualize how strongly semantic similarity between images aligns with neural similarity across visual ROIs (V1–LatOcc).
🧩 Function Overview
FunctionDescriptionload_results()Loads ROI-level RSA results from CSV filesplot_scatter()Plots semantic vs. neural similarity for each ROIplot_bar()Summarizes all ROI correlations in one figuresave_figures()Automatically saves generated plots to /figures/ 
⚙️ Dependencies
Python ≥ 3.10
Libraries: numpy, pandas, matplotlib, seaborn
📊 Example Output
Scatter plots showing semantic–neural relationship per ROI
Bar chart comparing Spearman correlations across all ROIs
All figures are automatically saved in the /figures/ directory.
