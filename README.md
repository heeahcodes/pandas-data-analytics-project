# pandas-data-analytics-project
## Case Study context
_A casual dining restaurant chain wants to understand tipping behavior to ensure fair compensation for servers. The company wants to understand whether customer smoking status and time of visit affect tipping behavior and further influences server compensation. Management suspects that factors such as smoking status and time of visit may influence tip amounts._

## 1. Objective : 
Evaluate whether tipping behavior differs between smokers and non-smokers, and whether this difference changes by time of day, after normalizing for bill size.

### 2. Source:
The analysis uses a publicly available dataset containing restaurant bills, tip amounts, smoking status, and time of visit.
_Tips dataset originally compiled by Bryant & Smith, made available via the `seaborn` Python library._

### 3. Methodology :
i. Created a normalized tip metric (tip as a percentage of total bill)
ii. Compared average tip percentages between smokers and non-smokers
iii. Segmented analysis by time of day (lunch vs dinner)
iv. Visualized results using grouped bar charts

#### 3.1 Why use a normalized figure?
Raw tip amounts are influenced by bill size. To ensure a fair comparison between groups, tips were normalized by total bill amount to compute tip percentage.

#### 3.2 Visualization
A bar chart of average tip percentage by smoker & time has been included to facilitate easier comparision between the presented figures.

### 4. Key Findings: 
i. Smokers tipped on average 0.39 percentage points more than non-smokers
ii. During lunch, smokers tipped slightly more
iii. During dinner, smokers tipped slightly less
iv. Differences were small overall

### 5. Interpretation
The results suggest that smokers on average tipped 0.39 percentage points more than non-smokers. When segmented by time of day, smokers tipped slightly more during lunch but slightly less during dinner. The differences were small, suggesting smoking status alone is not a strong predictor of tipping behavior. While the time of visit appears to have a greater influence, and observed differences may not be practically significant.
