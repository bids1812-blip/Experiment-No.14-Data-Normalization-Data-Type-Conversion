# Data Normalization & Data Type Conversion
## Aim
To understand and implement different data normalization techniques and perform data type conversion using Python libraries such as Pandas and NumPy.

## Theory
Data normalization is a preprocessing technique used in data analysis and machine learning to scale numerical values into a common range without distorting differences in the ranges of values.
Common normalization techniques include:
- Min-Max Normalization: Scales data between 0 and 1 using minimum and maximum values.
- Z-score Normalization: Standardizes data based on mean and standard deviation.
- Decimal Scaling: Moves the decimal point of values to bring them into a smaller range.
Data type conversion refers to changing the data format (e.g., integer to float) to ensure compatibility during computations and analysis.

## Tools Used
- Python
- Pandas Library – for data manipulation and analysis
- NumPy Library – for numerical operations

## Real Life Applications
- Data preprocessing in machine learning models
- E-commerce analytics (e.g., product pricing and sales comparison)
- Financial data analysis for scaling large values
- Healthcare data processing for standardizing patient metrics
- Data visualization for better comparison across variables

## Advantages
- Improves the accuracy and performance of machine learning models
- Helps in handling data with different scales
- Makes data easier to visualize and interpret
- Reduces bias caused by large numerical differences

## Disadvantages
- May lead to loss of original data interpretability
- Sensitive to outliers (especially Min-Max normalization)
- Requires proper understanding to choose the correct method
- An additional preprocessing step increases computation time

## Conclusion
In this experiment, various normalization techniques such as Min-Max, Z-score, and Decimal Scaling were successfully implemented. These methods help in transforming raw data into a standardized format, making it more suitable for analysis and machine learning applications. Understanding data normalization is essential for effective data preprocessing and accurate model performance.
