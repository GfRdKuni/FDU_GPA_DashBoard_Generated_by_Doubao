# FDU_GPA_DashBoard_Generated_by_Doubao

A lightweight, web-based GPA management tool designed specifically for Fudan University (FDU) students. This dashboard helps track, analyze, and visualize academic performance with simplicity and clarity.


## Overview
FDU_GPA_DashBoard_Generated_by_Doubao is a client-side web application built to streamline GPA tracking for FDU students. It eliminates the need for complex spreadsheets by offering intuitive data entry, bulk import, and visual insights into your academic progress.


## Key Features

### 📋 Course Management
- **Manual Entry**: Add individual courses with details like semester, course name, credits, grade, and notes.
- **Bulk Import**: Upload course data via CSV files for quick batch entry (supports standard FDU course formats).
- **Edit/Delete**: Easily modify or remove existing courses to keep records up-to-date.


### 📊 Data Visualization
- **Semester GPA Trend**: Line chart showing GPA changes across semesters.
- **Grade Distribution**: Pie chart breaking down grades (A+, A, B+, etc.) for quick performance overview.
- **GPA Range Analysis**: Bar chart visualizing how courses distribute across GPA ranges (0.0-0.5, 0.5-1.0, ..., 3.5-4.0).


### 🔍 Filtering & Sorting
- Filter courses by semester, grade, or search terms (course name, notes).
- Analyze performance within custom semester ranges to focus on specific academic periods.


### 📈 Key Stats
- At-a-glance metrics: total courses, total credits, average GPA, and breakdowns (GPA vs. PNP courses, honor courses).


## How to Use

1. **Add Courses**:
   - Click "Add New Course" to enter details manually (semester, credits, grade, etc.).
   - Or upload a CSV file via the "Upload CSV File" section (see [CSV Format](#csv-format) for requirements).

2. **Analyze Data**:
   - Use the filter dropdowns to narrow down courses by semester or grade.
   - Explore charts to identify trends in your academic performance.
   - Adjust the "Semester Range" to focus on specific time periods.

3. **Manage Records**:
   - Edit courses by clicking the pencil icon in the course table.
   - Delete courses with the trash icon (confirmations prevent accidental removal).

## CSV Format (for Bulk Import)
To import courses via CSV, use the following column order (no headers required):
```
Semester, [Ignored], [Ignored], Course Name, Credits, Grade, GPA, Notes
```
Example:
```
2023-2024 1,,,"Advanced Mathematics (H)",4,A+,4.000,"Honor course"
2023-2024 1,,,"General Physics",3,A,4.000,""
```


## Technologies Used
- **Frontend**: HTML5, Tailwind CSS v3, JavaScript (ES6+)
- **Visualization**: Chart.js
- **CSV Parsing**: PapaParse
- **Styling**: Font Awesome icons


## Installation & Setup
1. Clone or download this repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
3. No server or dependencies required—runs entirely client-side.


## Notes
- Data is stored locally in your browser (clearing browser data will reset your records).
- Optimized for FDU's grading system (supports 1/2/暑期 semesters, honor courses, and standard grading scales).
- For best results, use modern browsers (IE is not supported).


Built with assistance from Doubao, tailored for FDU students.
