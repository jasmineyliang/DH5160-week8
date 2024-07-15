# DH5160-week8

### Mini-Project: Health Data Visualization with ggplot2, Matplotlib, and Seaborn

### Data:
Suppose you have the following data for health metrics:

```r
patient_id <- 1:12
age <- c(20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75)
gender <- c("M", "F", "M", "F", "M", "F", "M", "F", "M", "F", "M", "F")
height <- c(180, 160, 175, 165, 170, 155, 185, 150, 190, 145, 195, 140)
weight <- c(75, 60, 80, 55, 85, 50, 90, 45, 95, 40, 100, 35)
cholesterol <- c(200, 180, 220, 190, 210, 170, 230, 160, 240, 150, 250, 140)
```

### Tasks in R:

1. **Create the Data Frame:**
   - Create a data frame named `health_data` with the given data.

2. **Inspect the Data:**
   - Display the first few rows and the structure of the data frame.

3. **Calculate BMI:**
   - Add a new column `bmi` to the data frame calculated as `weight / (height/100)^2`.

4. **Summary Statistics:**
   - Calculate summary statistics (mean, median, and standard deviation) for `age`, `bmi`, and `cholesterol`.

5. **Visualize Data:**
   - Create a scatter plot of `age` vs `bmi` with points colored by `gender`.
   - Create a histogram of `cholesterol`.
   - Create a box plot of `bmi` grouped by `gender`.


### Tasks in Python:

1. **Create the Data Frame:**
   - Create a data frame named `health_data` with the given data using pandas.

2. **Inspect the Data:**
   - Display the first few rows and the structure of the data frame.

3. **Calculate BMI:**
   - Add a new column `bmi` to the data frame calculated as `weight / (height/100)^2`.

4. **Summary Statistics:**
   - Calculate summary statistics (mean, median, and standard deviation) for `age`, `bmi`, and `cholesterol`.

5. **Visualize Data:**
   - Create a scatter plot of `age` vs `bmi` with points colored by `gender` using Matplotlib.
   - Create a histogram of `cholesterol` using Matplotlib.
   - Create a box plot of `bmi` grouped by `gender` using Seaborn.

