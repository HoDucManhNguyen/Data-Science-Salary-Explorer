# 🌍 Data Science Salary Explorer  
**Uncover Global Salary Trends in the Data Science Industry**

In the rapidly evolving world of data science, having access to reliable compensation data can guide career choices, salary negotiations, and hiring strategies. **Data Science Salary Explorer** is a Microsoft Excel-based analytical dashboard that enables users to explore, filter, and compare data-related job salaries across various countries, job titles, work types, and platforms.

Whether you're a data professional, a job seeker, or a hiring manager, this tool equips you with actionable insights for informed decision-making.

---

## 💡 The Problem This Tool Solves

Despite the growing demand for data science professionals, salary information remains fragmented across job boards, companies, and locations. This project helps to:

- Centralize and clean data science salary information  
- Provide interactive filtering by **country**, **job title**, **work schedule**, and **platform**  
- Offer a ready-to-use **salary calculator**  
- Highlight salary distributions across **job roles**, **employment types**, and **geographic regions**

---

## 📊 Excel Workbook Structure

The Excel file contains **7 organized worksheets**:

### 1. `Data`
The **master dataset**. Each row represents a job posting with fields such as:

- `job_title_short`, `job_location`, `company_name`  
- `job_schedule_type`, `job_work_from_home`, `job_skills`  
- `salary_year_avg`, `salary_hour_avg`, `job_country`  

> Ideal for pivot tables or filtered views.

### 2. `Validation`
Helper sheet used for **dropdown filters** and sorting. Contains:

- Cleaned job titles (`job_title_short_sorted`)  
- Job countries and schedule types for data validation  
- Frequency data (e.g., how often a job title appears)

### 3. `Salary Calculation`
An **interactive calculator** for users to estimate their salary:

- Select a **job title**, **country**, and **work type**  
- Get average annual compensation based on filtered criteria  
- Built-in logic uses data from the `Data` sheet

### 4. `Country`
Provides a **summary of average salaries by country**:

- Columns: `jobs_country`, `median_salary`  
- Includes filtered view data (`jobs_country_filter`)

### 5. `Title`
Salary distributions by **job titles**:

- Columns: `job_title_short_sorted`, `median_salary`  
- Useful for comparing roles like **Data Analyst** vs **ML Engineer**

### 6. `Type`
Breakdown of salaries by **employment types**:

- Full-time, Part-time, Internship, Contractor, Temp work  
- Visual aid for understanding salary differences by work type

### 7. `Platform`
Job source analysis (e.g., ZipRecruiter, Indeed):

- Insight into where **higher-paying jobs** are more frequently posted

---

## 🔍 How to Use

1. Open the Excel file in **Microsoft Excel** or **Google Sheets** (best in Excel for full interactivity).
2. Navigate to the `Salary Calculation` sheet to estimate expected salary.
3. Use Excel's **Filter** or **Pivot Table** features in the `Data` sheet to analyze:
   - Jobs by location, role, or company
   - Salary trends for remote vs on-site roles
   - Platforms that offer the most lucrative opportunities
4. Reference `Title`, `Country`, and `Type` sheets for summarized salary insights.

---

## 🧠 Why This Project Matters

| Use Case          | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Career Planning   | Understand global pay scales for data roles before relocating or negotiating. |
| Hiring Strategy   | Benchmark competitive salary offerings in your market.                      |
| Market Analysis   | Observe how location, job type, and platform affect compensation.           |
| Skills Focus      | Identify which skills (SQL, Python, AWS, etc.) appear in high-paying roles. |

---

## 🛠️ Built With

- **Microsoft Excel** – Data modeling, filters, dropdowns
- **Manual ETL** – Data gathered from job platforms (Indeed, LinkedIn, ZipRecruiter, etc.)
- **No macros required** – Compatible with most Excel versions

---

## 🚀 Getting Started

1. 📥 **Download** the Excel File
2. 📊 **Explore** the `Salary Calculation` tab first
3. 🔍 **Use filters** in the `Data` sheet for deep dives

---

## 📈 Sample Insights You Can Discover

- Average salary for **Senior Data Scientists** in the **US** working **Full-time**
- Top 5 countries paying the most for **Machine Learning Engineers**
- Platforms with the most **remote data jobs**
- Median salary by **job type** (e.g., Intern vs Full-Time)

---

## 👤 Author

**Manh Nguyen**  
📧 Email: [manhnhd.vn@gmail.com](mailto:manhnhd.vn@gmail.com)  
🔗 [LinkedIn: Manh Nguyen](https://linkedin.com/in/manhnguyen)
