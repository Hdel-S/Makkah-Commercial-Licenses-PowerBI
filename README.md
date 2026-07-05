# 📊 Makkah Commercial Licenses & Economic Activities Analysis (2025)
## لوحة مؤشرات المشهد التجاري والاستثماري بالعاصمة المقدسة لعام 2025م

An interactive Power BI Dashboard developed to analyze open data for commercial licenses in Makkah, Saudi Arabia, highlighting investment trends, seasonality, and sector sustainability aligned with Saudi Vision 2030.

مشروع تحليلي متكامل باستخدام **Power BI** لدراسة البيانات المفتوحة للرخص التجارية في مدينة مكة المكرمة، يهدف إلى تقديم رؤى استثمارية حول حركة السوق وتوزيع الأنشطة بما يتماشى مع مستهدفات رؤية المملكة 2030.

---

## 📸 Dashboard Preview / نظرة عامة على لوحة المؤشرات
(https://github.com/Hdel-S/Makkah-Commercial-Licenses-PowerBI/blob/main/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202026-07-05%20052402.png?raw=true)

---

## 🎯 Project Objectives / أهداف المشروع
* **Market Insights**: Identify the dominant commercial sectors and sub-activities in Makkah.
* **Seasonality Analysis**: Analyze license issuance trends across months and quarters (Q1-Q4) to detect peak seasons.
* **Investment Sustainability**: Calculate the average validity and duration of commercial licenses per industry.
* **تحليل حركة السوق**: تحديد الأنشطة التجارية والفرعية الأكثر هيمنة وطلباً في العاصمة المقدسة.
* **تحليل المواسم**: دراسة اتجاهات إصدار الرخص عبر الأشهر وأرباع السنة لمعرفة فترات الذروة.
* **استدامة الاستثمار**: حساب متوسط مدة صلاحية الرخص التجارية لكل قطاع لتقييم الاستقرار الاستثماري.

---

## 🛠️ Tech Stack & Methodology / التقنيات المستخدمة ومنهجية العمل

### 1. Data Cleaning & Transformation (Power Query)
* Filtered global dataset to focus strictly on **Makkah Municipality (أمانة العاصمة المقدسة)**.
* Handled date parsing issues (US/UK locale formats conversion) without losing data.
* Structured columns and categories for cleaner analytics.

### 2. Data Modeling & DAX
* Built a robust **Star Schema** by creating a dedicated Time Intelligence table (`TableDates`).
* Established active relationships between transaction timestamps and the calendar.
* Developed custom **DAX Measures & Calculated Columns** including:
  * `Total Licenses`: Total count of issued records.
  * `License Duration (Days)`: Calculated using `DATEDIFF` to measure longevity.
  * `Average License Duration`: To benchmark sector stability.

---

## 💡 Key Insights & Findings / أبرز الاستنتاجات والنتائج

1. **🚀 Q4 Growth Spike**: A massive surge in commercial license applications was detected during October, November, and December (exceeding 1,100 licenses/month), indicating high market momentum at year-end.
2. **🏨 Hospitality & Tourism Dominance**: "Tourist Accommodation" (النزل السياحية) topped the list, followed closely by restaurants and beverage shops, directly reflecting Makkah's unique economic nature in serving Hajj & Umrah pilgrims.
3. **🏫 Long-Term Investments**: Wholesale trade and educational sectors (Primary/Middle schools) achieved the highest license longevity (up to 5 years), proving high investment stability compared to retail or pop-up services.

---

## 📂 Repository Contents / محتويات المستودع
* 📁 `Makkah_Licenses_Dashboard.pbix`: The core Power BI project file.
* 📁 `Dataset/`: The cleaned open-data source file.
* 📝 `README.md`: Project documentation.

---

### 👤 Connect with Me / تواصل معي
If you have any questions, feedback, or job opportunities, feel free to reach out via:
* **LinkedIn**:www.linkedin.com/in/hadeel-alshahrani-84426510b

* **Email**: Hadeel.s.Alshahrani@gmail.com
