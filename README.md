# WeRateDogs Twitter Data Wrangling

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)  
[![Udacity Project](https://img.shields.io/badge/Udacity-Data%20Analyst%20Nanodegree-02b3e4.svg)](https://www.udacity.com/course/data-analyst-nanodegree--nd002)

This project was completed as part of **Udacity’s Data Analyst Nanodegree** and focuses on **data wrangling, cleaning, and analysis** of the **WeRateDogs** Twitter archive as of **August 1, 2017**.

WeRateDogs is a popular Twitter account known for humorously rating dogs, often assigning scores where the **numerator exceeds the denominator** (e.g., **12/10, 13/10**). The dataset, provided by Udacity, contains **tweet metadata** (tweet ID, timestamp, text) along with extracted details such as **dog names, ratings, and categorical classifications** (doggo, floofer, pupper, puppo).

## Data Dictionary (DOGTIONARY)

Below is a visual reference for the dog stage definitions used in this project:

![dogtionary](https://github.com/user-attachments/assets/215ae856-af67-46b9-b7c7-2408ae95e98f)

---

## Technical Implementation
- **Environment:** All data processing was performed using **Python (via Anaconda)** and executed in a **Jupyter Notebook**.
- **Data Sources:**
  - **Primary dataset**: WeRateDogs Twitter archive (provided by Udacity).
  - **Supplementary datasets**: Additional tweet details retrieved via the **Tweepy API**, following Twitter Inc.’s guidelines.

---

## Installation & Setup
To run this project on your local machine, follow these steps:

### **1. Install Dependencies**
Ensure you have **Python 3.8+** and the required libraries installed.

#### **Option 1: Using Anaconda (Recommended)**
```bash
conda create --name we_rate_dogs_env python=3.8
conda activate we_rate_dogs_env
```

#### **Option 2: Using Virtual Environment**
```bash
python -m venv we_rate_dogs_env
source we_rate_dogs_env/bin/activate  # Mac/Linux
we_rate_dogs_env\Scripts\activate  # Windows
```

### **2. Install Required Packages**
Run the following command to install dependencies:

```bash
pip install pandas numpy matplotlib seaborn requests tweepy jupyter
```

Alternatively, if a `requirements.txt` file is provided, install all dependencies at once:

```bash
pip install -r requirements.txt
```

### **3. Clone This Repository**
Navigate to your preferred directory in the terminal and run the following command:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/WeRateDogs-Data-Wrangling.git
cd WeRateDogs-Data-Wrangling
```

### **4. Launch Jupyter Notebook**
```bash
jupyter notebook
```
Then, open `wrangle_act.ipynb` in Jupyter to explore the dataset.

---

## Workflow
1. **Data Gathering** – Loaded provided datasets and retrieved supplementary data via the Twitter API.
2. **Data Cleaning** – Addressed **quality and tidiness** issues, correcting inconsistent formats.
3. **Exploratory & Explanatory Analysis** – Analyzed **rating trends, tweet engagement, and dog classifications**.

---

## Key Insights
The final analysis provides insights into:
- **Rating patterns**
- **User engagement**
- **Categorical distributions of dog stages**  

---

## Files Included
- 📜 `wrangle_act.ipynb` – Main Jupyter Notebook for data wrangling and analysis.
- 📄 `wrangle_report.pdf` – Summary of data cleaning steps.
- 📑 `act_report.pdf` – Summary of key insights and findings.
- 📝 `README.md` – Project documentation (this file).


---

### 🔗 References:
- [Udacity Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
- [WeRateDogs on Twitter](https://twitter.com/dog_rates)
- [Twitter API Documentation](https://developer.twitter.com/en/docs/twitter-api)

---

🔥 **If you found this project useful, consider giving it a ⭐ on GitHub!**  
