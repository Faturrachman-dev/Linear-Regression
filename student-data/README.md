# Dataset: Research Information of University Students

## Description

This dataset contains research information collected from university students. It includes demographic information, academic background, study habits, lifestyle factors, and academic performance metrics. The data can be used for various analyses, including predicting student performance, understanding factors influencing academic success, and exploring relationships between different student characteristics.

The dataset includes responses from students across different departments.

## Data Files

*   **ResearchInformation3.csv**: This CSV file contains the main dataset. Each row represents a student, and columns represent different variables collected.

## Column Descriptions

### Before One-Hot Encoding

The `ResearchInformation3.csv` file contains the following columns:

*   **Department**:  The department or academic program of the student (e.g., Business Administration, Computer Science and Engineering).
*   **Gender**:  Gender of the student (Male/Female).
*   **HSC**:  GPA or marks obtained in Higher Secondary Certificate (HSC) or equivalent examination.
*   **SSC**:  GPA or marks obtained in Secondary School Certificate (SSC) or equivalent examination.
*   **Income**:  Categorical income level of the student's family:
    *   "Low (Below 15,000)"
    *   "Lower middle (15,000-30,000)"
    *   "Upper middle (30,000-50,000)"
    *   "High (Above 50,000)"
    *(Note: Income values are likely in some local currency. Please refer to the original data source or research context for currency details if needed.)*
*   **Hometown**:  Type of hometown (Village/City).
*   **Computer**:  Self-reported hours of computer usage per day, categorized as:
    *   1 (Likely 0 hours)
    *   2 (Likely 1 hour)
    *   3 (Likely 2 hours)
    *   4 (Likely 3 hours)
    *   5 (Likely More than 3 hours)
*   **Preparation**:  Self-reported hours of study preparation per day, categorized as:
    *   "0-1 Hour"
    *   "2-3 Hours"
    *   "More than 3 Hours"
*   **Gaming**:  Self-reported hours of gaming per day, categorized as:
    *   "0-1 Hour"
    *   "2-3 Hours"
    *   "More than 3 Hours"
*   **Attendance**:  Self-reported class attendance percentage, categorized as:
    *   "Below 40%"
    *   "40%-59%"
    *   "60%-79%"
    *   "80%-100%"
*   **Job**:  Indicates if the student has a job (Yes/No).
*   **English**:  Marks or grade in English subject. (Likely numerical, but scale not specified in provided context. Further investigation of the original source might be needed for precise interpretation).
*   **Extra**:  Indicates participation in extracurricular activities (Yes/No).
*   **Semester**:  Current semester of the student (e.g., 6th, 7th, 3rd).
*   **Last**:  GPA or CGPA of the last semester.
*   **Overall**: Overall GPA or CGPA up to the current semester.

### After One-Hot Encoding

Index(['HSC', 'SSC', 'English', 'Last', 'Overall', 'Gender_Female',
       'Gender_Male', 'Hometown_City', 'Hometown_Village', 'Computer_1',
       'Computer_2', 'Computer_3', 'Computer_4', 'Computer_5',
       'Preparation_0-1 Hour', 'Preparation_2-3 Hours',
       'Preparation_More than 3 Hours', 'Gaming_0-1 Hour', 'Gaming_2-3 Hours',
       'Gaming_More than 3 Hours', 'Attendance_40%-59%', 'Attendance_60%-79%',
       'Attendance_80%-100%', 'Attendance_Below 40%', 'Job_No', 'Job_Yes',
       'Extra_No', 'Extra_Yes', 'Semester_10th', 'Semester_11th',
       'Semester_12th', 'Semester_2nd', 'Semester_3rd', 'Semester_4th',
       'Semester_5th', 'Semester_6th', 'Semester_7th', 'Semester_8th',
       'Semester_9th', 'Department_Business Administration',
       'Department_Computer Science and Engineering', 'Department_Economics',
       'Department_Electrical and Electronic Engineering',
       'Department_English',
       'Department_Journalism, Communication and Media Studies',
       'Department_Law and Human Rights', 'Department_Political Science',
       'Department_Public Health', 'Department_Sociology',
       'Income_High (Above 50,000)', 'Income_High (Above 50,000) ',
       'Income_High (Above 50,000)  ', 'Income_Low (Below 15,000)',
       'Income_Low (Below 15,000) ', 'Income_Lower middle (15,000-30,000)',
       'Income_Lower middle (15,000-30,000) ',
       'Income_Lower middle (15,000-30,000)  ',
       'Income_Upper middle (30,000-50,000)',
       'Income_Upper middle (30,000-50,000) '],
      dtype='object')

## Data Source

This dataset was likely collected through surveys or data gathering from university students.  *(The exact source and collection methodology are not explicitly detailed in the information available. Further details might be found in associated publications if available on Mendeley Data or from the data authors.)*

## Intended Uses

This dataset can be used for:

*   **Educational Data Mining:**  Analyzing factors affecting student performance.
*   **Predictive Modeling:** Building models to predict student GPA or academic success.
*   **Social Science Research:**  Investigating relationships between student demographics, lifestyle, and academic outcomes.
*   **Developing Student Support Systems:** Identifying students at risk based on various factors.

## License

*(The license information is not explicitly provided on the Mendeley Data page snippet. Please check the Mendeley Data page for license or terms of use information associated with the dataset. If no license is specified, standard data usage ethics apply.)*

## How to Use this Dataset

1.  Download the `ResearchInformation3.csv` file.
2.  Use data analysis tools like Python with pandas, R, or other statistical software to load and explore the data.
3.  Refer to the "Column Descriptions" section above to understand each variable.
4.  Preprocess the data as needed for your analysis (e.g., handle categorical variables, scale numerical features).
5.  Develop your models or conduct your research based on your specific questions.

---
**Note:** This README is based on the information available from the Mendeley Data page and the column names in your CSV snippet.  For a more comprehensive README, it's always best to refer to any original documentation or publications associated with the dataset on Mendeley Data itself, or from the data creators if possible. You might find more details about data collection methods, variable scales, and intended use there.