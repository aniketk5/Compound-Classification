# Compound-Classification
Objective:
Build the classification model on given data to classify the compounds as either ‘Musk’ or ‘Non-Musk’ compounds.

Model Used: 
Multilayer perceptron model (MLP) is used because MLPs are suitable for classification prediction problems where inputs are assigned a class or label. This model is generally used when data is often provided in a tabular format, such as you would see in a CSV file or a spreadsheet.

Preprocessing:
1) The unwanted data columns are removed from the data.
2) Splitting the conformation name model into 3 parts
   1. Molecule Name
   2. ISO -- Sterioisomer Number
   3. CONF -- Conformation Number
3) Deleting Unwanted Columns
4) Shuffling the Dataset to generate randomness
5) Separating Input & Output
6) Converting dataframe object to numpy array
