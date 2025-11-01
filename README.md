## 💰 Advanced Finance Power BI Dashboard Project

This repository contains the files and documentation for an advanced Power BI dashboard project focused on financial data analysis. This project demonstrates sophisticated techniques in **DAX**, **dynamic visualization**, and **user experience (UX) design** to turn a simple dataset into a professional, highly interactive report.

### ✨ Key Features and Technical Highlights

This dashboard was built not just for data display, but for dynamic functionality and a clean user interface.

| Feature Area | Description | Technical Implementation |
| :--- | :--- | :--- |
| **Dynamic Measures** | Allows the user to select and view different financial metrics (Income, Savings, Target) on a single visual. | Leveraged a **Slicer Table** and **DAX Measures** to conditionally filter and display the correct metric line on the chart. |
| **Dynamic Title** | The chart's title automatically updates to reflect the currently selected measure. | A specific **DAX Measure** was created to return the selected value from the slicer, which was then applied to the visual's **Title field**. |
| **Report Reset (UX)** | A single-click button to instantly clear all filters and revert the report to its default state. | Utilized **Power BI Bookmarks** to capture the initial state and apply that bookmark's action to a dedicated **Refresh/Reset Button**. |
| **Custom Filters** | Implemented a clean, toggleable pop-up window for the date filter. | Achieved using **Bookmarks** and the **Selection Pane** to manage the visibility of the date slicer container and button. |
| **Enhanced Tooltips** | Custom, data-rich tooltips were designed for the main visuals to provide additional context on hover. | Implemented custom **Report Page Tooltips** for an elevated user experience. |

---

### 🛠️ Technologies and Tools Used

* **Platform:** Power BI Desktop
* **Language:** Data Analysis Expressions (**DAX**)
* **Design:** Dark-themed UI/UX for a modern and attractive look
* **Core Concepts:** Bookmarks, Selection Pane, Custom Tooltips, Conditional Formatting

---

### 🚀 Getting Started

To explore this project, you will need Power BI Desktop installed on your system.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/mrkarannn03/Finance-Dashboard
    ```
2.  **Open the Project File:**
    * Navigate to the cloned folder.
    * Open the `.pbix` file (e.g., `Finance_Dashboard_Project.pbix`).
3.  **Explore the Report:**
    * Test the **Dynamic Slicer** next to the main trend chart.
    * Click the **Calendar Icon** to view the custom pop-up filter.
    * Try filtering data, then use the **Refresh Button** to see the bookmark action work.

---

### 🎥 Watch the Tutorial

If you'd like to understand the step-by-step logic behind this project, including the detailed DAX and Bookmark setup, please check out the full tutorial:

[Advanced! Finance Power BI Dashboard Project tutorial for beginners](https://youtu.be/gkJ_Siugnac)

### 🧑‍💻 Author

* **[Karan Singh]** - [Your GitHub Profile Link: https://github.com/mrkarannn03/] | [Your LinkedIn Profile Link: https://www.linkedin.com/in/karansingh2006/]
