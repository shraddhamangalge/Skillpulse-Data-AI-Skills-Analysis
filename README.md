# SkillPulse: Mapping Data & AI Skills in the Job Market

**A Python-Based Web Scraping and Job Market Analysis Project**

---

## 1. Project Overview

SkillPulse is a Python-based web scraping and data analysis project designed to explore the demand for Data and AI-related skills in the job market.

The project collects job listings from the Himalayas job platform through its public Jobs API. The collected data is processed, cleaned, and analyzed to identify relevant job opportunities and extract frequently mentioned technical skills from job descriptions.

The primary goal is to understand which technical skills and technologies are commonly required by employers for Data and AI-related positions.

## 2. Project Objectives

- Collect real-world job listing data using Python and API requests.
- Retrieve multiple batches of job records using cursor-based pagination.
- Convert JSON API responses into structured datasets.
- Perform data inspection, cleaning, and preprocessing.
- Extract meaningful information from HTML-based job descriptions.
- Identify Data and AI-related job opportunities.
- Extract technical skills using keyword matching and regular expressions.
- Analyze skill frequency and identify commonly requested technologies.
- Present findings through data visualizations.

## 3. Data Source

**Source:** Himalayas Jobs Platform  
**Data Collection Method:** Public Jobs API

The API provides job-related information, including:

- Job title and company name
- Employment type and seniority level
- Salary information
- Location restrictions
- Job categories
- Job descriptions
- Publication dates
- Application links

The project uses API-based data collection rather than directly scraping the rendered webpage. BeautifulSoup is used to extract readable text from HTML content within job descriptions.

## 4. Technologies and Libraries

| Technology | Application |
|---|---|
| Python | Core programming language |
| Requests | Sending HTTP requests and retrieving API data |
| JSON | Processing API responses |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| BeautifulSoup | HTML parsing and text extraction |
| Regular Expressions | Text cleaning and skill extraction |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Counter | Counting extracted technical skills |
| Jupyter Notebook | Development and experimentation |

## 5. Project Implementation

### Step 1: API Integration and Data Collection
Established a connection with the Himalayas Jobs API using the Python Requests library and retrieved job listing data in JSON format.

### Step 2: Pagination
Implemented cursor-based pagination to retrieve multiple batches of job records. This allowed the collection of 200 job listings through 10 API requests, with 20 records requested per batch.

### Step 3: Data Transformation
Converted the collected JSON job records into a Pandas DataFrame to create a structured dataset for analysis.

### Step 4: Data Inspection
Examined dataset dimensions, column names, data types, missing values, and duplicate records to understand data quality.

### Step 5: Data Cleaning and Preprocessing
Used BeautifulSoup to remove HTML tags from job descriptions and prepared the text for further processing.

### Step 6: Job Filtering
Filtered job listings using relevant keywords from job titles and categories to identify Data and AI-related opportunities.

### Step 7: Technical Skill Extraction
Used keyword matching and regular expressions to identify technical skills mentioned in job descriptions.

### Step 8: Exploratory Data Analysis
Analyzed the frequency of extracted skills to understand which technologies appeared most often in the filtered job listings.

### Step 9: Data Visualization
Used Matplotlib and Seaborn to create visual representations of skill demand and communicate the findings.

## 6. Key Results

The project collected and analyzed job listing data with the following results:

| Analysis Metric | Result |
|---|---:|
| Total jobs reported by the API | 115,415 |
| Job records collected | 200 |
| Data and AI-related jobs identified | 13 |
| Unique companies | 13 |
| Role categories | 3 |
| Locations identified | 2 |
| Technical skills identified | 19 |
| Jobs containing salary information | 8 |

### Most Frequently Mentioned Technical Skills

| Technical Skill | Number of Job Listings |
|---|---:|
| Excel | 7 |
| Python | 5 |
| AWS | 5 |
| SQL | 4 |
| Tableau | 4 |
| Azure | 3 |
| Machine Learning | 3 |
| Databricks | 2 |
| Power BI | 2 |
| GCP | 2 |

### Key Findings

- Excel was the most frequently identified skill in the filtered dataset.
- Python and AWS were also commonly mentioned in job descriptions.
- SQL and Tableau appeared in multiple job listings.
- Cloud platforms such as AWS, Azure, and GCP were represented.
- Machine Learning was another skill identified in the analyzed opportunities.

**Note:** These findings are based on the 200 collected job records and 13 filtered Data and AI-related listings. They represent the analyzed sample and should not be interpreted as a complete representation of the job market.

## 7. Project Structure

```text
SkillPulse/
│
├── SkillPulse_Organized.ipynb
│
├── README.md
│
└── requirements.txt
```

## 8. Installation and Execution

Follow the steps below to run the project locally.

**Prerequisites:**
- Python installed on your system.
- Jupyter Notebook.
- Internet connection for API access.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/SkillPulse.git
```

### Step 2: Navigate to the Project Directory

```bash
cd SkillPulse
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Execute the Notebook

Open `SkillPulse_Organized.ipynb` and execute the cells sequentially to perform data collection, preprocessing, analysis, and visualization.

## 9. Requirements

The project uses the following Python libraries:

```text
requests
pandas
numpy
beautifulsoup4
matplotlib
seaborn
jupyter
```

## 10. Skills Demonstrated

This project demonstrates practical knowledge of:

- Python programming and data structures
- API integration and HTTP requests
- JSON data handling
- Cursor-based pagination
- Web scraping concepts
- HTML parsing using BeautifulSoup
- Data cleaning and preprocessing
- Text processing using Regular Expressions
- Data manipulation using Pandas and NumPy
- Exploratory Data Analysis (EDA)
- Keyword-based information extraction
- Data visualization and analytical reporting

## 11. Conclusion

SkillPulse demonstrates the application of Python for collecting, processing, and analyzing real-world job market data.

By retrieving job listings through an API and analyzing Data and AI-related opportunities, the project identifies commonly mentioned technical skills and provides insights into employer requirements.

The project provided practical experience in API-based data collection, pagination, HTML parsing, data preprocessing, text analysis, and data visualization.

---

## Author

**Shraddha Mangalge**

Information Technology Graduate | Aspiring Python Developer

**Project:** SkillPulse – Mapping Data & AI Skills in the Job Market

**Technologies:** Python | Requests | BeautifulSoup | Pandas | NumPy | Matplotlib | Seaborn
