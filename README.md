# Lisa-Mulyawati---Capstone-Project-Titanic-Analysis

## 📌 Project Overview
Proyek ini menggunakan dataset Titanic bawaan dari library Seaborn untuk menganalisis faktor-faktor yang memengaruhi peluang bertahan hidup penumpang. Analisis difokuskan pada gender, kelas sosial (Pclass), dan status keluarga (SibSp, Parch).

## 📂 Dataset
- **Sumber**: Titanic dataset dari `seaborn` library (dataset publik bawaan).
- **Cara akses**: 
  ```python
  import seaborn as sns
  df = sns.load_dataset("titanic")

## 🔍 Analysis Process
1. **Data Cleaning**: menghapus missing values, fokus pada kolom relevan (`Survived`, `Sex`, `Pclass`, `Age`).
2. **Exploratory Data Analysis (EDA)**: distribusi survival rate berdasarkan gender dan kelas sosial.
3. **Visualization**: bar chart & cross-tab survival rate.
4. **Insight & Findings**: ringkasan temuan utama.
5. **Conclusion & Recommendations**: implikasi kebijakan & insight bisnis.

## 📊 Insight & Findings
- Perempuan memiliki survival rate lebih tinggi (sekitar 74%) dibandingkan laki-laki (18%).
- Penumpang kelas 1 memiliki survival rate jauh lebih tinggi dibandingkan kelas 3.
- Faktor gender dan kelas sosial adalah determinan penting survival rate.

## ✅ Conclusion & Recommendations
- **Kebijakan keselamatan transportasi**: perlu ada prioritas yang lebih sistematis untuk kelompok rentan (wanita & anak-anak).
- **Bisnis & hospitality industry**: menunjukkan pentingnya *customer segmentation* dan *priority service*. Perlakuan berbeda terhadap kelas sosial berdampak langsung pada outcome.
- **Analisis risiko**: model Titanic bisa dipakai sebagai analogi untuk manajemen risiko modern — memastikan akses keselamatan & layanan tidak hanya berdasarkan kelas ekonomi.
