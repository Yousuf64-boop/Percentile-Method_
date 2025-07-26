📊 Percentile Method - Outlier Detection
This notebook demonstrates how to detect and handle outliers using the Percentile Method. This technique is applied to a dataset containing height and weight data categorized by gender.

📁 Dataset
weight-height.csv

Columns:

Gender

Height

Weight

📌 What is the Percentile Method?
Outliers are values outside a specified percentile range.

Typically:

Lower bound = 1st percentile

Upper bound = 99th percentile

Data points outside this range are considered outliers.

🔍 Steps Covered
Load and inspect the dataset

Visualize distributions using seaborn

Define 1st and 99th percentile thresholds

Filter out extreme values

Visualize cleaned data

🧰 Libraries Used
pandas

numpy

seaborn

matplotlib

🖼️ Visual Output
Before-and-after KDE plots

Histogram representation of outliers
