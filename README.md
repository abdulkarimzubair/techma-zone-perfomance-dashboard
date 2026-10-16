# 📊 TECHMA ZONE Performance Dashboard

An interactive **Power BI** dashboard that analyzes student enrollment, academic performance, job placement, and revenue for TECHMA ZONE, a tech training institute, from 2020 to 2026.

> **Goal:** turn raw student data into clear answers to three questions: *Who enrolls? Who succeeds? Who gets hired?*

---

## 🎥 Demo

<!-- Replace with your own links -->
- **Video walkthrough:** `[add LinkedIn / YouTube link]`
- **Live report:** `[add Power BI Service link, if published]`

![Dashboard Preview](images/dashboard-page-1.png)
![Student Analysis Preview](images/dashboard-page-2.png)

---

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Students | 13.1K |
| Passed Out | 9.8K |
| Passing Ratio | 74.4% |
| Dropouts | 1.3K (9.90%) |
| Total Job Placements | 5.4K |
| Job Placement Rate | 40.95% |
| Average Student Age | 23 |

---

## 📑 Report Pages

### Page 1: Performance Overview
- **KPI cards:** students, passed out, dropout, dropout rate, placements, placement %, average age
- **Students enrolled by category:** Programming, Marketing, Data & AI, Design
- **Passing ratio:** gauge chart
- **Yearly gross revenue:** area chart trend (2020–2026)
- **Delivery mode distribution:** Onsite / Online / Hybrid

### Page 2: Student Analysis
- **Employment status at registration:** Student, Unemployed/Fresh Graduate, Employed (upskilling), Freelancer
- **Student performance table:** education level, prior experience, pass/fail, placement status, year
- **Total students enrolled by gender** across years
- **Job placement by gender:** pie chart
- Male/Female student and placement counts

---

## 🎛️ Interactivity

- **Slicers:** Year, Category, Course Name
- **Cross-filtering:** selecting any visual updates the rest of the page
- **Page navigation:** sidebar buttons between pages

---

## 🛠️ Tools & Skills

- **Power BI Desktop**
- **DAX:** measures for passing ratio, dropout rate, placement rate, and so on
- **Data modeling:** relationships across Student, Course, Batch, Campus, Company, Enrollment, Payments, and Placements tables
- **Data visualization & dashboard design**

---

## 🗂️ Data Model

Tables used in the model:

`Student` · `Enrollment` · `Course` · `Batch` · `Campus` · `Payments` · `Placements` · `Company`

> Add a screenshot of your **Model view** here: `![Data Model](images/data-model.png)`

---

## 📁 Repository Structure

```
├── TECHMA_ZONE_Dashboard.pbix   # Power BI report file
├── data/                        # Source data (or sample data)
├── images/                      # Dashboard screenshots
└── README.md
```

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `TECHMA_ZONE_Dashboard.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path under **Transform data → Data source settings**.
4. Use the slicers to explore by year, category, and course.

---

## 💡 Key Insights

- Programming leads enrollment among all categories.
- The overall passing ratio is **74.4%**, while the dropout rate is **9.90%**.
- About **4 in 10** students are placed in jobs, which shows room to improve placement support.
- Revenue grew steadily over the years. *(Note: confirm whether 2026 is a partial year.)*

---

## 🔮 Future Improvements

- Add tooltips and drill-through pages per course
- Add a "Reset filters" bookmark button
- Add a placement-by-company and salary analysis page
- Publish to Power BI Service with scheduled refresh

---

## 👤 Author

**[Your Name]**
🔗 [LinkedIn](https://linkedin.com/in/your-profile) · 💻 [GitHub](https://github.com/your-username)

---

⭐ If you found this project useful, please give it a star!
