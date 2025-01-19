# **Bank Client Data Analysis and Insights**

### **Overview**
This project performs a comprehensive analysis of a bank client dataset to understand customer behavior, analyze marketing campaign success, and predict subscription outcomes. The project involves:
- Exploratory Data Analysis (EDA) to uncover key patterns.
- Visualization dashboards for storytelling.
- Predictive modeling to determine factors influencing customer subscriptions.

---

### **Dataset Description**
The dataset contains information about bank clients, campaign details, and subscription outcomes. Below are key attributes:

- **Client Information**:
  - `age`: Age of the client.
  - `job`: Job type (e.g., "admin.", "technician", "retired").
  - `marital`: Marital status ("married", "single", "divorced").
  - `education`: Education level ("primary", "secondary", "tertiary").
  - `balance`: Average yearly balance in euros.
  
- **Loan and Financial Status**:
  - `default`: Has credit in default? ("yes" or "no").
  - `housing`: Has housing loan? ("yes" or "no").
  - `loan`: Has personal loan? ("yes" or "no").
  
- **Campaign Details**:
  - `contact`: Contact type ("telephone", "cellular").
  - `duration`: Last contact duration in seconds.
  - `poutcome`: Outcome of the previous campaign ("success", "failure", "unknown").

---

### **Steps Taken**
1. **Understanding the Dataset**:
   - Preprocessed the dataset to handle missing values, outliers, and inconsistencies.
   - Summarized key statistics to understand data distributions.

2. **Exploratory Data Analysis**:
   - Generated insights using bar charts, scatter plots, and heatmaps.
   - Key findings:
     - Retired clients and high-balance clients have higher subscription rates.
     - Cellular contact methods perform better compared to telephone.

3. **Dashboard Creation**:
   - Created **interactive visualizations** to present key metrics.
   - Analyzed subscription trends across demographics.

4. **Model Selection and Evaluation**:
   - Implemented Logistic Regression for binary classification.
   - Evaluated model performance with metrics such as accuracy, precision, and recall.

---

### **Dashboards**
- **Dashboard 1**: Subscription trends and key metrics.
- **Dashboard 2**: Comparative analysis across campaigns.

---

### **Project Findings**
1. **Key Insights**:
   - Cellular contact methods lead to better outcomes.
   - Higher balance and retired individuals are significant contributors to subscription success.
   - Subscription rates vary across job types and marital statuses.

2. **Recommendations**:
   - Focus marketing campaigns on high-balance clients and retirees.
   - Optimize call durations and leverage cellular contact methods.

---

### **Technologies Used**
- **Programming Languages**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Scikit-learn
- **Visualization Tools**: Dashboards created using Excel/Python
- **Documentation**: PowerPoint Presentation

---

### **Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya0305030/7104
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scripts EDA and modeling:
   ```bash
   power bi hackathon.pbix
   python main.ipynb
   ```

---

### **File Structure**
```
📂 Bank-Client-Analysis
├── 📄 README.md (Project Documentation)
├── 📄 requirements.txt (Dependencies)
├── 📄 hackathon.pbix (Exploratory Data Analysis Script)
├── 📄 main.ipynb (Predictive Modeling Script)
├── 📊 dashboards/
│   ├── dashboard 1.png
│   ├── dashboard 2.png
├── 📄 Bank Client Data Analysis and Visualization.pptx (PowerPoint Presentation)
├── 📂 data/
│   ├── test.csv (Dataset)
```

---

## 📋 Authors
- Prabhat Kumar Ganguli
- Aditya
- Nikhil kumar

---

### **License**
This project is licensed under the MIT License. See the LICENSE file for details.
