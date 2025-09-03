# 📊 HR Analytics Dashboard (Power BI)

## 📌 Project Overview

This Power BI project is a comprehensive HR Analytics dashboard designed to provide a 360-degree view of an organization's workforce. It focuses on analyzing employee demographics, identifying key drivers of attrition, and correlating performance and satisfaction data to improve retention strategies.

## ✨ Key Features & Goals

- **Page 1: Workforce Overview & Demographics:** A high-level summary of the employee base.
- **Page 2: Attrition & Retention Analysis:** A deep dive into employee turnover with actionable insights.
- **Page 3: Performance & Satisfaction:** An analysis connecting employee performance to job satisfaction.

## 🛠️ Tools & Technologies

- **Power BI Desktop:** Used for end-to-end dashboard development.
- **Power Query:** Utilized for data cleaning and transformation.
- **DAX (Data Analysis Expressions):** Created advanced measures for complex business logic.

## 📈 Key Skills Demonstrated

- **Advanced DAX & Problem-Solving:** Solved complex issues using `RANKX` for dynamic ranking and `DIVIDE` for rate calculations.
- **Data Transformation:** Adapted to data limitations by creating new columns like `Tenure Group` in Power Query.
- **Visual Storytelling:** Crafted a narrative across multiple pages, using the right visuals to tell a clear and compelling story.
- **Actionable Insights:** Translated data into specific insights for HR and management, such as identifying departments with high attrition or top-performing employees.
- **Interactive Design:** Implemented slicers and filters for a user-friendly and dynamic experience.

## 🚀 Challenges & Solutions

| **Challenge** | **Solution** |
| :--- | :--- |
| **Missing Time-Series Data:** No `Hire Date` column for employee growth trends. | I created a `Tenure Group` column in Power Query to analyze the experience distribution of the workforce as a valuable alternative insight. |
| **Top N Filter Failure:** The standard visual filter was not working correctly. | I created a robust DAX measure using `RANKX` to dynamically rank employees, ensuring a reliable Top 10 list. This demonstrates a more advanced DAX skill. |
| **Raw Attrition Data:** The `Attrition` column contained text values ('Yes'/'No') not suitable for calculations. | I transformed this column in Power Query into a numeric flag (`1`/`0`), which was then used to calculate the `Attrition Rate %`. |

## 💡 Key Insights from the Analysis

- **Employee Demographics:** The dashboard provides a clear breakdown of the workforce by age group, department, and job role.
- **Attrition Drivers:** The analysis reveals which departments and tenure groups have the highest attrition rates, pinpointing areas for targeted retention efforts.
- **Performance & Satisfaction:** The dashboard helps management identify high-performing employees and analyze the relationship between job satisfaction and employee turnover.

---

### 🖼️ Dashboard Screenshots

**Page 1: Workforce Overview & Demographics**

![Wrokforce overview](./WORKFORCE%20OVER%20VIEW.PNG)
**Page 2: Attrition & Retention Analysis**

![Wrokforce Attrition](./WORKFORCE%20ATTRITION.PNG)
**Page 3: Performance & Satisfaction**

![Wrokforce Satisfaction](./WORKFORCE%20SATISFACTION.PNG)

## 💬 Feedback & Support  

Thank you for visiting my GitHub repository! 🙌  
I truly appreciate your time and interest in my project.  

If you have any feedback, suggestions, or ideas for improvement, feel free to **open an issue** or reach out — your input means a lot and will help me make this project even better. 💡  

⭐ If you found this project helpful or inspiring, please consider giving it a **star** on GitHub — it really motivates me to keep building and sharing!  




