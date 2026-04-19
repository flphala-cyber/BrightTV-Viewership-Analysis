# 📺 BrightTV Viewership Analysis

## 🎯 Objective

Analyze BrightTV viewership data to understand audience behavior, content performance, and engagement patterns, and provide actionable insights for Customer Value Management (CVM).

---

## ❓ Key Business Questions

* Which channels generate the highest viewing hours?
* Which audience segments (age, province) are most active?
* What are the peak viewing days?
* Which time periods drive the most engagement?
* How engaged are viewers across different content?

---

## 🗂️ Data Sources

This project uses two primary datasets:

* **User Profiles**

  * UserID, Age, Gender, Race, Province
* **Viewership Data**

  * UserID, Channel, Record Date & Time, Duration

---

## 🛠️ Tools & Technologies

* **SQL (Databricks)** → Data cleaning, transformation, aggregation
* **Excel** → Pivot tables and data analysis
* **Canva / PowerPoint** → Presentation and visualization
* **Miro** → Data architecture and workflow design

---

## ⚙️ Data Processing Workflow

1. **Data Cleaning**

   * Renamed columns (Channel2 → Channel)
   * Converted timestamps
   * Converted duration to seconds/minutes

2. **Profile Cleaning**

   * Standardized province names
   * Created age groups

3. **Data Integration**

   * Joined viewership and profile datasets using UserID

4. **Feature Engineering**

   * Day_Name (Monday–Sunday)
   * Day_Type (Weekday/Weekend)
   * Time_Period (Morning, Afternoon, Prime Time, Late Night)
   * Viewing_Intensity (High, Medium, Low)

5. **Aggregation**

   * Created master summary table with key metrics:

     * Total Views
     * Unique Viewers
     * Total Hours
     * Engagement levels

---

## 📊 Analysis & Dashboard

The analysis focuses on:

* **Content Performance** → Channel-level insights
* **Audience Segmentation** → Age group & demographics
* **Geographic Analysis** → Province-level performance
* **Behavioral Analysis** → Day and time patterns
* **Engagement Analysis** → Viewer intensity levels

Dashboard outputs are available in the `dashboard/` folder.

---

## 📁 Project Structure

```bash
BrightTV-Viewership-Analysis/
│
├── data/                # Raw dataset
├── sql/                 # SQL scripts
├── dashboard/           # Pivot tables & charts
├── presentation/        # Slides (PPT)
├── miro/                # Workflow diagram
└── README.md
```

---

## 📈 Key Insights

* 📺 Sports and live event channels dominate viewing hours
* 📅 Weekend viewing is highest, especially Saturday
* ⏰ Afternoon and Prime Time are peak viewing periods
* 👥 The 25–44 age group is the core audience
* 📍 Gauteng leads in overall viewership

---

## 💡 Recommendations

* Invest more in **sports and live event content**
* Focus marketing efforts on **weekends**
* Target the **25–44 audience segment**
* Optimize scheduling for **Afternoon and Prime Time**
* Develop strategies to improve **low engagement users**

---

## 🚀 Project Outcome

This project demonstrates:

* Data cleaning and transformation
* SQL-based analysis
* Feature engineering
* Data aggregation
* Dashboard creation
* Business insight generation

---

## 👤 Author

**Frans Phala**
Aspiring Data Analyst | SQL | Excel | Data Visualization

