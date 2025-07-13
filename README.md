# 📊 Placement Eligibility Streamlit App

This is a data-driven Streamlit application that evaluates student eligibility for placements based on various performance metrics like programming, soft skills, and placement readiness.

---

## 🔧 Tech Stack

- 🐍 Python
- 📦 Faker (for synthetic data)
- 💾 SQLite (relational database)
- 📊 Streamlit (dashboard UI)
- 🐼 Pandas (data handling)

---

## 📁 Project Structure

```
Placement-Eligibility-App/
├── placement_app.py          # Streamlit app
├── data_generator.py         # Generates fake student records
├── create_tables.py          # Creates required DB tables
├── requirements.txt          # Dependencies
├── students.db               # SQLite database (excluded via .gitignore)
└── README.md
```

---

## 🛠️ Setup Instructions

### ✅ 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/placement-eligibility-app.git
cd placement-eligibility-app
```

### ✅ 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### ✅ 3. Create Tables and Generate Data

```bash
python create_tables.py
python data_generator.py
```

### ✅ 4. Run the App

```bash
streamlit run placement_app.py
```

---

## 🔍 Features

- Generate 500 synthetic student records using Faker
- Store and manage data in a normalized SQLite database
- Dynamic filtering based on custom eligibility criteria
- View programming, soft skills, and placement performance
- Easily extendable with SQL analytics

---

## 📊 Sample Eligibility Criteria

- Programming Problems Solved > 50
- Communication Skills > 75
- Placement Status: Ready or Placed

---

## 📌 Future Improvements

- Add filters to Streamlit sidebar
- Visualizations for soft skills distribution
- Export eligible students as CSV

---

## 📄 License

This project is for educational and demonstration purposes.

---

## ✨ Author

Created by [Kavitha] — part of the GUVI Capstone Project.
