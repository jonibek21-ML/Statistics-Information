# 📊 Student Performance Analysis

## 📌 Project haqida

Bu loyiha **studentlar performance (natijalar)** datasetini tahlil qilishga bag‘ishlangan.
Asosiy maqsad — turli faktorlar (gender, ota-ona ta’limi, o‘qish vaqti va boshqalar) student natijalariga qanday ta’sir qilishini aniqlash.

---

## ⚙️ Ishlatilgan texnologiyalar

* 🐍 Python
* 📦 NumPy
* 🐼 Pandas
* 📊 Matplotlib
* 🎨 Seaborn
* 🧇 PyWaffle
* 🌳 Squarify

---

## 📂 Dataset haqida

Dataset quyidagi ustunlardan iborat:

* 🎓 MathScore, ReadingScore, WritingScore
* 👩‍🎓 Gender
* 👨‍👩‍👧 ParentEduc
* 💍 ParentMaritalStatus
* 🍱 LunchType
* 🧑‍🤝‍🧑 EthnicGroup
* ⏱ WklyStudyHours

---

## 🔍 Asosiy jarayonlar (Pipeline)

### 1️⃣ Data yuklash

```python
df = pd.read_csv("Expanded_data_with_more_features.csv")
```

### 2️⃣ Data tekshirish

* `.head()`
* `.info()`
* `.describe()`

---

### 3️⃣ Missing value (NaN) bilan ishlash

* NaN bor columnlarni aniqlash
* Categoric → mode bilan to‘ldirish
* Numeric → median bilan to‘ldirish

---

### 4️⃣ Data Visualization

* 🥧 Gender distribution (Pie Chart)
* 📊 Parent Education (Line + Scatter)
* 🧇 Lunch Type (Waffle Chart)
* 🌳 Marital Status (Treemap)
* 📈 Study Hours (Bar Chart)

---

### 5️⃣ Advanced Visualization

* 🔗 Pairplot (featurelar orasidagi bog‘liqlik)
* 🌡 Correlation Heatmap
* 📉 Histogram & KDE
* 📊 Score Distribution

---

## 📊 Natijalar

* Gender bo‘yicha natijalar farqi ko‘rildi
* Ota-ona ta’limi student natijalariga ta’sir qiladi
* Study hours oshgani sari natijalar yaxshilanadi
* Fanlar o‘rtasida kuchli correlation mavjud

---

## 🚀 Qanday ishlatish

1. Repository clone qil:

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Kutubxonalarni o‘rnat:

```bash
pip install -r requirements.txt
```

3. Notebookni ishga tushur:

```bash
jupyter notebook
```

---

## 📦 requirements.txt

```txt
numpy
pandas
matplotlib
seaborn
pywaffle
squarify
```

---

## 🤝 Contribution

Pull requestlar ochiq 👍
Xatolik topsang — issue och!

---

## ⭐ Xulosa

Bu loyiha orqali:

* Data cleaning
* EDA (Exploratory Data Analysis)
* Visualization

ko‘nikmalari mustahkamlanadi.
