#  Exploratory Data Analysis on Restaurant Tips

This project performs an **Exploratory Data Analysis (EDA)** on the popular Seaborn `tips` dataset.  
The dataset contains information about restaurant bills, tips, customer demographics, and dining context.  
Our goal is to understand **what factors influence tipping behavior**.

---

##  Dataset
We use the inbuilt **Seaborn Tips Dataset**, which contains the following features:

- **total_bill**: Total bill amount (USD)  
- **tip**: Tip amount given (USD)  
- **sex**: Gender of the person paying  
- **smoker**: Whether the person is a smoker or not  
- **day**: Day of the week  
- **time**: Lunch or Dinner  
- **size**: Size of the dining party  

---

##  Steps in EDA
1. **Importing libraries** – NumPy, Pandas, Seaborn, Matplotlib  
2. **Loading dataset** – `sns.load_dataset("tips")`  
3. **Data Cleaning** – Checking shape, missing values, null heatmap  
4. **Descriptive Statistics** – Summary of numeric & categorical features  
5. **Correlation Analysis** – Understanding relationships between bill, tip, size  
6. **Visualizations**  
   - Distribution plotsl  
   - Boxplots 
   - Heatmaps   
   - Scatter plots
   - joint plot 

---

##  Key Insights
- 💡 **Total bill and tip are positively correlated** – higher bills generally mean higher tips.  
- 🍷 **Dinner meals attract higher tips than lunch**.  
- 🚬 **Smokers’ groups show different tipping behavior compared to non-smokers**.  
- 👥 **Larger groups tend to give higher absolute tips but not necessarily higher percentages**.  
- 👫 **Gender differences in tipping are visible but less significant compared to bill size**.  

---

