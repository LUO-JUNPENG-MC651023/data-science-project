# data-science-project
# Student Performance Analysis: The Impact of Study Time and Sleep

## 1. Problem / Research Question
**Research Question:** How does the number of weekly study hours affect a student's final score, and how do sleep duration and attendance rate moderate this relationship? 
This project aims to explore whether simply studying more guarantees higher grades, or if other health and behavioral factors (like getting enough sleep) play a critical role.

## 2. Dataset Source and Usage Permissions
*   **Source:** A simulated dataset created for educational purposes to demonstrate data visualization and analysis techniques in Python.
*   **Dataset structure:** 24 rows, containing `student_id`, `study_hours_per_week`, `sleep_hours_per_night`, `attendance_rate`, and `final_score`.
*   **Permissions:** The data is entirely simulated and contains no real personal information (PII). It is free to use and modify for educational assignments.

## 3. Methods and Tools Used
*   **Programming Language:** Python
*   **Libraries:** Pandas (for data manipulation), Matplotlib (for visualization).
*   **Methods:** 
    *   Exploratory Data Analysis (EDA).
    *   Scatter plot with multiple visual encodings (X/Y position, color, size).
    *   Linear regression trend line to show the overall positive correlation.

## 4. Key Findings and One Limitation
**Key Findings:**
*   There is a clear positive correlation between weekly study hours and final scores.
*   **The Sleep Moderator:** Students who sleep less than 6 hours per night perform significantly worse than their peers who study similar amounts but get adequate sleep. Sleep is essential to realize the benefits of studying.
*   Attendance rate also shows a positive, though secondary, impact on the final score.

**Limitation:**
*   The dataset is simulated with a small sample size (n=24). Therefore, the findings demonstrate a conceptual relationship rather than generalizable empirical facts. Additionally, correlation does not imply causation. 
*   In the visualization, mapping attendance rate to point size can make it difficult to compare exact values when points overlap.

## 5. Instructions for Running the Analysis
To reproduce the analysis:
1. Clone this repository or download the files.
2. Ensure you have Python installed. Install the required libraries by running:
   `pip install -r requirements.txt`
3. Open the Jupyter Notebook (`analysis.ipynb`) or run the Python script (`analysis.py`).
4. The script will read `student_scores.csv` and generate the visualizations saved in the repository.

---
*Note: No sensitive data, passwords, or API keys are included in this repository.*
