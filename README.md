# Markdown

# Biological Data Processing Seminar Assignment

## Course Information
**Course**: Biological Data Processing (2023-2024)  
**Training Dataset**: *Cattle response to various olfactorial stimuli*  
**Location**: Freising, Germany, Experimental Station of the Munich Technical University  

## Study Overview
The aim of this study was to assess the response of cattle to olfactorial stimuli, including predator and control odours. The measure of response was the time spent in an area with mineral licks, where cows had to enter after encountering odours placed on specific material at the entrance to the mineral lick.

### Dataset Description
The dataset includes the following columns:
- **Date**: Date of observation.
- **Time A**: Time of the day when the cow entered the mineral lick area.
- **Time B**: Time of the day when the cow left the mineral lick area.
- **Time (min)**: Time that the cow spent in the mineral lick area (calculated as the difference between Time B and A).
- **Cow number**: Individual tag of the animal. Animals without ear tags are marked with missing values.
- **Weight (kg)**: The weight of the animal.
- **Odour**: Experimentally prepared odours, categorized as:
  - **Wolf**: Sympatric predator.
  - **Lycaon**: African wild dog as an allopatric predator.
  - **Eucalyptus**: A control odour.
  - **Control**: Sterile, odour-free textile visible at the entrance.
  - **NONE**: No textile material, representing the baseline long-term situation.
- **Pasture**: Two pastures where the experiments were conducted: K06 and K08.

---

## Assignment Tasks

### Task 1: Descriptive Statistics
1. Provide a table with descriptive statistics for:
   - **Time spent in the mineral lick area**
   - **Weight**
2. Perform the analysis:
   - **a)** For the overall dataset.
   - **b)** Categorized by **Pasture** and **Odour type**.

---

### Task 2: Distribution of Time Variable
1. Test the distribution of the variable **Time (min)** (duration).
2. Create a graph illustrating the distribution.
3. Comment on the distribution and write a conclusion.

---

### Task 3: Weight Comparison Between Pastures
1. Test whether there is a difference in the **mean weight of cows** between the two pastures (**K06** and **K08**).
2. Steps to follow:
   - Select and justify the appropriate statistical test.
   - Perform the analysis.
   - Write up the results.
   - Create a graph visualizing the result.
   - Describe the result verbally in the text.

---

### Task 4: Frequency of Cow Visits
1. Calculate the **frequency of cow visits** to mineral licks for each **odour type** per pasture.

---

### Task 5: Time Spent in Response to Odours
1. Test whether there is a difference in the **time spent in the mineral lick area** in response to various odours.
2. Check if the response to odours **differs between pastures**.
3. Exclude the **NONE** odour data since this is a baseline and not a control.
4. Steps to follow:
   - Select and justify the appropriate statistical test.
   - Perform the analysis.
   - Write the results verbally in the text.
   - Create a graph illustrating the findings.

---

### Task 6: Daily Growth Rate
1. Calculate the **daily growth rate** of cows during the entire investigation period.
2. Create a graph visualizing the daily growth rate.
3. Test whether the daily growth rate differs between the two pastures.

---

### Task 7: Full Timestamp
1. Create a column with the **full timestamp**, including:
   - **Date**
   - **Time**
   - **Time zone information**

---

## Deliverables
- Tables and graphs for each task.
- Written descriptions and justifications for the statistical tests applied.
- Conclusions and interpretations of the results.
```
