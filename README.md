# 🦠 COVID-19 India Data Analysis Dashboard (Tableau)

## Interactive dashboard: https://us-east-1.online.tableau.com/t/jeevanrishi0-dc0d2712a1/views/Project_Final_Viz_JeevanKumar/Dashboard
## Data story link: https://us-east-1.online.tableau.com/t/jeevanrishi0-dc0d2712a1/views/Datastory/DataStory
## Overview
This Tableau project explores COVID-19 trends in India using a detailed dataset that includes confirmed cases, recoveries, deaths, and vaccination rates across various states. The project emphasizes **visual storytelling** with a somber and respectful black-themed design, representing the seriousness and human cost of the pandemic.

The dashboard aims to highlight key insights such as:
- Variation in vaccination rates by state
- Correlation between vaccination coverage and case/death counts
- Temporal patterns in confirmed, recovered, and fatal cases
![Dashboard Final](https://github.com/user-attachments/assets/f8dadaca-9a7d-4e22-bf1b-3913a84dd591)


---

## 🎯 Lead Insight

> The most interesting discovery from the COVID-19 dataset is the **significant variation in vaccination rates across different states in India**, which correlates with the varying number of confirmed cases and deaths.

---

## 🎨 Design Philosophy

A **black background** is used throughout the worksheets and dashboard to create a **unified visual theme**. This color choice represents the gravity of the pandemic, commemorating the lives lost and acknowledging the seriousness of the health crisis.

---

## 📊 Worksheets Breakdown

### 🗺️ Worksheet 1: COVID-19 Cases and Deaths by State (Map View)
**Purpose**: Visualize total deaths by state to identify the most affected regions.

- **Aggregation/Granularity**: State-level aggregation of total deaths
- **Ranking**: States sorted in descending order of death count
- **Visual Marks**:
  - `Color`: Darker shades indicate higher deaths
  - `Tooltip`: Displays total deaths on hover
- **Functions Used**: String formatting for state names
- **Interactivity**: 
  - `Filter`: Select state → updates linked charts accordingly

---

### 📈 Worksheet 2: COVID-19 Cases Trend by State (Line Chart)
**Purpose**: Show time series trends for confirmed, recovered, and death cases by state.

- **Aggregation/Granularity**: State-level trend over time
- **Sorting**: Alphabetically by state name
- **Visual Marks**:
  - `Color`: Different lines for confirmed, recovered, and deaths
- **Interactivity**:
  - `Filter`: Select state → updates all visuals accordingly

---

## 📁 Project Structure

This project currently contains 4 Tableau worksheets (first half). The second half is under development and will expand on:
- Vaccination analysis
- Case fatality rate visualization
- Predictive time series trends

---

## 🛠️ Tools & Techniques

- **Tableau Desktop**
- **String and Date Functions**
- **Interactivity using Filters**
- **Custom Tooltip Design**
- **Geographical and Temporal Visualization**

---

## 📍 Future Enhancements
- Add additional worksheets for:
  - Vaccination penetration vs case severity
  - Case fatality and positivity rate dashboards
- Deploy full dashboard to Tableau Public for broader access
- Add hover-based story annotations for user navigation

---

## 🕊️ Acknowledgment

This project is a tribute to the lives affected by COVID-19 and aims to provide actionable insights for researchers, healthcare providers, and policymakers.

---

## 📸 Screenshots

| Map View (Deaths by State) | Trend Line View (Cases Over Time) |
|----------------------------|----------------------------|
| ![MAP Total deaths by state](https://github.com/user-attachments/assets/517d3520-aac3-4516-9721-6e85c0e52e30)
 | ![Covid Cases By State](https://github.com/user-attachments/assets/776c5b3d-c038-46fa-a719-c09a80b1d803)
 |

> *(Note: Replace the above placeholder image paths with real screenshots from your project in an `assets/` folder in your repo.)*

---

## 🧠 Author

**Jeevan Kumar Banoth**  
Graduate Student | Data Analyst | Tableau & Python Enthusiast  
📧 [jbanoth@umassd.edu](mailto:jbanoth@umassd.edu)  
🔗 [LinkedIn](https://www.linkedin.com/in/jeevankumarbanoth) | [GitHub](https://github.com/jeevanbanoth)

---

## 📜 License

This project is open-source and free to use under the MIT License.
