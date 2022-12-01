# LomaGeology

## Schedule
 - October 5: read our paper on a ML pipeline for geochemical data. Also, a cleaned dataset - the first row with variable names with just numeric data. 
 
- October 10: Descriptive statistics of the dataset including a correlation analysis and ANOVA with R. 
 
- October 17: The application of K-means and PCA to the data with Python or R. Visualize the results. 
 
- October 24: A report of your findings in the previous weeks. 
 
- October 31: An improved report. This report will be submitted to LLU so we can get their feedback. According to their feedback we’re going to plan for next month.

## Reports
- October 17, 2022
    - Clean up the data to include only the major elements
    - Possibly run K-means on that cleaned up data
    - (Maybe) Create a map of the major elements using GIS data?

- October 24, 2022
    - Create a document to include results based on 5 principal components (Send to Loma Linda University)
        - Sections such as PC1 vs PC2, PC1 vs PC2, etc.
    - Use scikit learn, run data through data classification model

- November 14, 2022
    - Create a document
        - Include PCA results
        - Include summary report of decision trees
            - What classes should be used?

- November 30, 2022
    - Separate samples by class
        - Run PCA analysis on each class individually
        - Group classes by similarity to discover which ones might be candidates for aggregation
        - Hopefully, grouping similar classes should result in more accurate decision trees with fewer classes
        - Maybe do a GIS overlay?