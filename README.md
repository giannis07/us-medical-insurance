# U.S. Medical Insurance Project

## **Project Context & Overview** 🎓

This  project was developed as part of the **Data and Programming Foundations for A.I.** skill path on**Codecademy**.

The goal is to analyze the `insurance.csv` dataset of U.S. medical insurance costs to uncover insights from both numerical and categorical variables using **Python** and its standard **`csv` library** while practicing founational data analysis and programming skills.

---

## **Dataset Description**

The dataset used in this project is `insurance.csv`, which contains information about individuals medical insurance charges in the United States. Each row represents a person, and the columns include:

- **age**: Age of the primary beneficiary (in years)
- **sex**: Gender of the beneficiary (male or female)
- **bmi**: Body Mass Index, a measure of body fat based on height and weight
- **children**: Number of children/dependents covered by the insurance
- **smoker**: Smoking status of the beneficiary (yes or no)
- **region**: Residential area in the U.S. (northeast, northwest, southeast, southwest)
- **charges**: Individual medical insurance costs billed by health insurance

---

## ***Analysis Goals and Objectives** 🎯

The primary objectives of this analysis were:

1. **Calculate Numerical Averages**: Find the mean value for key numerical variables (e.g., average age, average BMI).
2. **Calculate Average Charges per Category**: Determine the average insurance charge for varius subgroups (smokerstatus, sex, region).
3. **Statistical Distribution**: Find the population count for categorical variables (e.g., the total number of males an females).

---

## **Implementation Methodology** 💻

The analysis was implemented in a **Jupyter Notebook** following these structured steps:

1. **Date Ingestion & Preparation:**
	* The standard **`csv` library** was imported.
	* **Seperate empty lists** were created for each attribute.
	* The data was read using `csv.DictReader()` and values were **appended** to their respective lists.
	
2. **Analysis Functions:**
	Three distinct functions were developed to perform the required analysis:
	
	| Function| Purpsose |
	| :--- | :--- |
	| `calculate_average(lst,lst_name)` | Calculates the **mean average** of numerical data (e.g., age, BMI). |
	| `calculate_average_charge_by_category(lst, charges)` | Calculates the **mean charge** for each subgroup within categorical data (e.g., average charge for smokers). |
	| `num_sexes()` | Calculates the **total count** of males and females in the dataset. |
	
---

## **Key Findings** 📈

The primary insights extracted from the dataset analysis are summarized below:

* **Average Demographics:**
	* **Average Age:** **39.21** years.
	* **Average BMI:** **30.66**. 

* **Population Distribution:**
	* **Males:** 676
	* **Females:** 662

* **Average Charges by Lifestyle and Demographics:**

	| Category | Average Charge (USD) | Insight |
	|:--- | :--- | :--- |
	| **Smoker** | **$32,050.23** | Smoking status is the most significant cost driver. |
    | **Non-Smoker** | **$8,434.27** | |
    | **Male** | **$13,956.75** | Males have a slightly higher average charge than females. |
    | **Female** | **$12,569.58** | |
	
* **Average Charges by Region:**
    | Region | Average Charge (USD) |
    | :--- | :--- |
    | **Southeast** | **$14,735.41** | (Highest average charge) |
    | **Northeast** | $13,406.38$ |
    | **Northwest** | $12,417.58$ |
    | **Southwest** | $12,346.94$ | (Lowest average charge) |

---

## **How to Run the Project** 🚀

1. **File Download**: Download the zip file containing the dataset (`insurance.csv`) and the **Jupyter Notebook** with the code.
2. **Enviroment Setup**: Ensure you have Python and Jupyter installed.
3. **Execution**: Open the Jupyter Notebook and run the cells sequentially to view the analysis and findings.

---

## ***Technologies Used**

* **Python 3.x**
* **Jupyter Notebook**
* **`csv` Library**

--- 

## Author ✍️
 
Created by Ioannis Mousouleas - https://github.com/giannis07

---

## License 📄

MIT License
