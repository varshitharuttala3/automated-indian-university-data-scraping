# Indian University & Course Data Scraping Project

## 📌 Project Overview
This project performs automated web scraping to collect university and course information from official Indian university websites.

The extracted data is structured and exported into an Excel file with relational integrity between universities and courses.

---

## 🎯 Objective
- Scrape 8 Indian universities
- Extract minimum 8 courses per university
- Maintain clean structured dataset
- Ensure proper relational linking using unique IDs
- Export final data into Excel with two sheets

---

## 🛠 Tools & Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas
- OpenPyXL
- UUID (for unique ID generation)

---

## 📂 Project Structure

### Sheet 1: Universities
Contains:
- university_id (Unique)
- university_name
- country
- city
- website

### Sheet 2: Courses
Contains:
- course_id (Unique)
- university_id (Linked to Universities sheet)
- course_name
- level
- discipline
- duration
- fees
- eligibility

---

## 🔗 Relational Integrity
Each course is linked to its respective university using `university_id`.  
This ensures proper database-style structure between both sheets.

---

## ⚙️ Key Features
- Fully automated scraping (no manual copy-paste)
- Unique ID generation
- Duplicate removal
- Clean structured dataset
- Ethical scraping practices (headers + request delay)
- Organized Excel output

---

## 📊 Output
Final output file:

University_Course_Data.xlsx

Contains:
- 8 Universities
- Minimum 8 Courses per university
- Structured and clean dataset

---

## 🚀 How to Run

1. Open Google Colab
2. Install required libraries
3. Run all cells
4. Download the generated Excel file

---

## 📌 Note
All data is collected from official university websites for educational and evaluation purposes only.

---

## 👩‍💻 Author
Varshitha
