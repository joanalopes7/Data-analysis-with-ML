# Data-analysis-with-ML


This project was conceived in an academic context, in the curricular unit "Intelligent Systems for Bioinformatics" of the master's degree in Bioinformatics and was developed by:

- [Carlos Gomes](https://github.com/CarlosGomes00)
- [Diogo Esteves](https://github.com/dasesteves)
- [Joana Lopes](https://github.com/joanalopes7)
- [Tiago Miranda](https://github.com/tiagomiranda24)


This project involves the analysis of a dataset using machine learning algorithms with Python as the programming language. The work will be documented in a Jupyter Notebook, organized into sections, which will include the steps of the analysis performed. Each section will succinctly explain the procedures undertaken and the decisions made throughout the analysis.

The dataset chosen for this project is derived from the [DisGeNET](https://tdcommons.ai/multi_pred_tasks/gdi#disgenet) platform, specifically focusing on gene-disease associations. DisGeNET is a comprehensive knowledge platform that integrates data from various sources to provide extensive information on the relationships between genes and diseases.

To use the DisGeNET dataset with TDC, you can use the following code:
```python
from tdc.multi_pred import GDA
data = GDA(name='DisGeNET')
split = data.get_split()
