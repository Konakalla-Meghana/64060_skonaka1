# Bank Marketing Dataset Analysis 

Welcome to the Bank Marketing Dataset Analysis project! This repository contains Python code and analysis of the dataset.

This assignment contains the following tasks:

### 1. Download a dataset 
- The dataset used is the bank marketing dataset from the UCI  Machine Learning repository.
- The 'ucimlrepo' library is used to directly fetch the dataset.

### 2. Import the Dataset into Python 
- Features are loaded into pandas Dataframe for analysis.

### 3. Descriptive Statistics 
- Firstly, I identified the qualitative and quantitative variables present in the dataset. Qualitative variables are of data type "object," while quantitative variables are either of type "int" or "float."
- For descriptive statistics, the describe() function was employed.

### 4. Variable Transformation 
- The balance Variable is transformed using a square root.

### 5. Plotting 
- The histogram for the 'age' Variable is plotted.
- A scatterplot for 'age' and 'balance' is generated.

### 6. Transformation Explanation 
- transformation choice: square root of "balance" variable.
- Reasoning: Applied for better visualization and identification of underlying patterns.
- Insights: Useful for skewed distribution.

### 7.  Plot Interpretation 
#### Histogram of Age 
- Majority of individuals fall within a certain age range, suggesting a target age group.
#### Scatterplot of Age vs. Balance
- People with higher ages tend to have higher balances; however, there is a significant amount of variability in the data. Notably, there are many individuals with lower ages who exhibit higher balances. As age increases beyond 60-70, the balances tend to decrease again

### Libraries used
- `ucimlrepo`: Library for fetching datasets from the UCI Machine Learning Repository.
- `pandas`:  Data manipulation and analysis library.
- `matplotlib`: Plotting library
- `seaborn`: Data visualization library.

### Acknowledgment 
- Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)


### Additional Information 
- Make sure that the Python environment meets the library requirements that are specified in the code.
- Double-check the Git repository link for accessibility and include all necessary files.

## Running the Code
1. Open the provided Google Colab notebook.
2. Run the code cells sequentially.

## Repository Structure

- **FML_Assignment.ipynb**: Google Colab notebook containing the Python code.
- **README.md**: This file, provides instructions and information about the assignment.
