# Cars Dataset Analysis

This repository contains a Python analysis project on a classic Cars dataset. The dataset includes information about various car models, their fuel efficiency, engine specifications, production years, and origin countries.

## Dataset Overview

- **Rows:** 398  
- **Columns:** 9  
- **Key Columns:**  
  - `mpg` (Miles per gallon)  
  - `cylinders`  
  - `displacement`  
  - `horsepower`  
  - `weight`  
  - `acceleration`  
  - `model_year`  
  - `origin` (Country of origin)  
  - `name` (Car model name)  

## Project Tasks & Insights

1. **Loading and exploring data:**  
   - Read the dataset from CSV  
   - Display dataset shape, columns, and sample data  

2. **Data manipulation:**  
   - Created new columns (e.g., horsepower to weight ratio)  
   - Set appropriate indexes  

3. **Key Questions Answered:**  
   - Identified the car model with the highest horsepower  
   - Counted cars with fuel efficiency (mpg) ≥ 35  
   - Determined the most common origin for cars with horsepower > 100 and weight < 3000  
   - Calculated the mean acceleration of cars from Japan  
   - Found the model year with the highest average mpg  
   - Discovered car(s) with the best horsepower-to-weight ratio among cars with above-median mpg  

4. **Visualizations:**  
   - Multi-line plot showing the evolution of average mpg over the years by origin
   - output1.png
   - Scatterplot of horsepower vs. weight, colored by origin and sized by mpg
   - output2.png

5. **Advanced Analysis:**  
   - Defined “consistent” car models as those produced over multiple years with very low mpg variation (std deviation < 1.0)  
   - Identified these consistent models, reporting their name, number of appearances, and average mpg  

## Tools & Libraries Used

- Python 3.x  
- Pandas for data manipulation  
- NumPy for numerical operations  
- Matplotlib and Seaborn for visualization  
