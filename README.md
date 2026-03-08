# 🎯 AtliQo Credit Card — Customer Segmentation & A/B Testing


A two-phase data analysis project for **AtliQo Credit Card** to identify potential target customer groups through **Exploratory Data Analysis (EDA)** and validate marketing strategies using **A/B Testing**.

---

## 📌 Overview

AtliQo wants to identify the right target audience for their credit card product. This project analyzes customer data across income, age, gender, and location dimensions — and validates which customer segments respond best to campaigns using A/B testing.

---

## 🗂️ Project Phases

### ✅ Phase 1 — EDA & Customer Segmentation
Perform exploratory data analysis to understand customer distribution and identify high-potential target groups.

**Key tasks:**
- Income distribution analysis across occupation, gender, and location
- Filter valid customers (age between **15 and 85**)
- Customer distribution across age groups:
  - 👦 **Youngsters:** 18–25 years
  - 💼 **Mid-Age Professionals:** 26–48 years
  - 🧓 **Seniors:** 49–65 years
- Customer distribution by location and gender


### ✅ Phase 2 — A/B Testing
Validate which customer segments show the strongest response to AtliQo credit card campaigns.

**Key areas tested:**
- 📊 **Income Group Response** — Which income bracket converts better?
- 👥 **Age Group Response** — Which age group responds more to campaigns?

---



## 🔍 Phase 1 — EDA Highlights

| Analysis | Description |
|---|---|
| **Income Distribution** | Breakdown by occupation, gender, and location |
| **Age Filtering** | Valid age range: 15–85 years |
| **Age Group Segmentation** | Youngsters / Mid-Age Professionals / Seniors |
| **Location & Gender Split** | Customer count per region and gender |

---

## 🧪 Phase 2 — A/B Testing Highlights

| Test | Groups Compared | Metric |
|---|---|---|
| **Income Group Response** | Low / Mid / High Income | Conversion / Engagement Rate |
| **Age Group Response** | Youngsters / Mid-Age / Seniors | Response Rate to Campaign |

> Statistical significance was evaluated to determine the winning segment for each test.

---

## ⚙️ How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/saibalajijammu/customer_segmentation.git
cd customer_segmentation
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebooks
```bash
jupyter notebook
```
Open `phase_1_atliqo_bank.ipynb` for EDA and `phase_2_atliqo_bank.ipynb` for A/B testing.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scipy
jupyter
```

---

## 🛠️ Tech Stack

- **Language:** Python
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Statistical Testing:** SciPy
- **Environment:** Jupyter Notebook

---


## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> ⭐ If you found this project helpful, please give it a star!
