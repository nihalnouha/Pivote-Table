# Pivote-Table
Load Dataset: We start by loading the dataset into a DataFrame. In this example, I've created a sample DataFrame called train_data to simulate your dataset.

Create Pivot Table: We use the pivot_table() function to create a pivot table. In this example, we want to summarize the average age of passengers based on their survival status (Survived) and gender (Sex). We specify the index as 'Survived', columns as 'Sex', values as 'Age', and aggregation function as 'mean' to calculate the average age.

Display Pivot Table: Finally, we print the pivot table to visualize the summarized data.

I add the task number 5 to number 4 .
We first load or create a DataFrame named df containing our dataset.(as you know I did it in task 4)
We then use the drop_duplicates() method on the DataFrame to remove duplicate rows.
The resulting DataFrame without duplicates is stored in a new variable named df_no_duplicates.
Finally, we print the DataFrame df_no_duplicates to display the dataset without duplicates.
This code will identify and remove duplicate rows based on all columns by default. You can customize the behavior by specifying the subset of columns to consider for identifying duplicates using the subset parameter of the drop_duplicates() method.