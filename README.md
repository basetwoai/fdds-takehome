# Take-Home Challenge: Forward Deployed Data Scientist 
August 2022

### Context

The successful candidate in this role will be working closely with Basetwo's customers and their data, ensuring their success with our simulation products. This involves preparing data, assisting them with modelling using Basetwo's platform, as well as presenting and communicating results.

In this task you will be using a dataset generated in a simulation of a penicillin bioreactor. You are asked to use Python to prepare the data for analysis, answer some questions about it, and communicate your findings in a clear and compelling format.

If you need further information or clarification beyond the instructions found here, please reach out to joshua at bastwo dot ai as soon as possible. 

### Instructions

1. Download the dataset found in the zip file in this repo.
2. Write Python code to prepare the data, and answer the questions found below. Please add comments to describe what your code is doing.
3. Prepare visualizations to describe the data and display the answers to the questions as though you are delivering a report to a client. You may use the tools of your choice for this task.
4. Submit all of your code and outputs via email to joshua at basetwo dot ai.


### About the data

This dataset contains data representing 100 separate runs or "batches" from a penicillin bioreactor. Each batch is monitored at regular intervals, one row per interval. Columns represent parameters of the system; some are changing over time, others are fixed design parameters. Units are included in the column names.   


### Questions
A) There is a problem with some of the column headers, impacting the Batch ID column. Identify what went wrong with the column headers and fix it so you can use the Batch ID column.

B) After fixing the column headers you will notice that some number of columns at the end of the dataset seem to have no name or use. Drop them.

C) Identify which column(s) represent the output we would want to optimize for. Which batch produced the greatest yield at the end of the batch?

D) Describe the trajectory of the highest yielding batch and make a recommendation for how to ensure a high yield in future batches.


#### Acknowledgments
Thanks to Stephen Goldrick at UCL Biochemical Society for making this data publicly available.