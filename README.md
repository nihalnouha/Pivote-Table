# Pivote-Table
Load Dataset: We start by loading the dataset into a DataFrame. In this example, I've created a sample DataFrame called train_data to simulate your dataset.

Create Pivot Table: We use the pivot_table() function to create a pivot table. In this example, we want to summarize the average age of passengers based on their survival status (Survived) and gender (Sex). We specify the index as 'Survived', columns as 'Sex', values as 'Age', and aggregation function as 'mean' to calculate the average age.

Display Pivot Table: Finally, we print the pivot table to visualize the summarized data.

