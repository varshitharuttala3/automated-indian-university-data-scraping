# Indian University & Course Data Scraping Project

## 📌 Internship Project

This project was completed as part of the **AI/ML & Web Scraping Data Entry Intern** assignment at **HelpStudyAbroad**.

The objective was to scrape university and course data from official websites and structure it professionally in an Excel file with proper relational integrity.

---

## 🎯 Project Objective

- Select 8 universities
- Scrape minimum 8 courses per university
- Structure data into clean datasets
- Maintain relational integrity using unique IDs
- Export final output into Excel with two sheets
- Ensure automated scraping (no manual copy-paste)

---

## 🛠 Technologies Used

- Python  
- Requests  
- BeautifulSoup  
- Pandas  
- OpenPyXL  
- UUID (for unique ID generation)

---

## 📂 Dataset Structure

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

Each course record is linked to its respective university using `university_id`.  
This ensures proper structured data similar to database design principles.

---

## ⚙️ Key Features

- Fully automated web scraping
- Unique ID generation
- Duplicate removal
- Clean structured dataset
- Ethical scraping practices (request headers and delay)
- Organized Excel export with multiple sheets

---

## 📊 Final Output

The final output file:

**University_Course_Data.xlsx**

Includes:
- 8 Indian Universities
- Minimum 8 courses per university
- Structured and clean data
- Proper linking between both sheets

---

## 🚀 How to Run the Project

1. Open Google Colab
2. Install required libraries
3. Run all notebook cells
4. Download the generated Excel file

---

## 📌 Disclaimer

Data was collected from official university websites strictly for academic and internship evaluation purposes.

---

## 👩‍💻 Author

Varshitha  
AI/ML Enthusiast  
