# 🧹 GUI-Based Excel Data Cleaning Automation

A Python-based desktop application that automates common Excel data-cleaning tasks through a simple and user-friendly Graphical User Interface (GUI).

Instead of manually cleaning spreadsheets, users can select an Excel file, choose the required cleaning operations, select an output folder, and generate a cleaned Excel file automatically.

---

## 📌 Project Overview

Data cleaning is an important step in any data analysis workflow. Real-world Excel datasets often contain duplicate records, completely blank rows, unnecessary spaces, and inconsistent text formatting.

This project was developed to automate these repetitive data-cleaning tasks using Python.

The application provides users with selectable cleaning options, allowing them to perform only the transformations they need.

---

## ✨ Key Features

- 📂 Browse and select an Excel input file
- 🧹 Remove duplicate rows
- 🗑️ Remove completely blank rows
- ✂️ Remove leading and trailing spaces from text columns
- 🔤 Convert text columns to Title Case
- 📁 Select a custom output folder
- ⚡ Automatically generate a cleaned Excel file
- 🔄 Reset selected file and folder paths
- 🔄 Reset all cleaning options
- ⚠️ Error handling and user-friendly error messages
- ✅ Success notification after successful processing

---

## 🖥️ How the Application Works

The application follows a simple workflow:

```text
Select Excel File
       ↓
Select Cleaning Options
       ↓
Select Output Folder
       ↓
Click "Clean Data"
       ↓
Python Processes the Dataset
       ↓
Cleaned Excel File Generated

🧹 Available Data Cleaning Operations
1. Remove Duplicate Rows

Identifies and removes duplicate records from the dataset.

2. Remove Blank Rows

Removes rows where all values are blank.

3. Remove Leading & Trailing Spaces

Removes unnecessary spaces from text columns.

Example:

Before:   "  Rahul Sharma  "
After:    "Rahul Sharma"
4. Convert Text to Title Case

Standardizes text capitalization.

Example:

Before:   "rAHUL shARMA"
After:    "Rahul Sharma"
🛠️ Technologies Used
Programming Language
Python
Libraries
Pandas
Tkinter
OpenPyXL
OS
📚 Skills & Concepts Demonstrated
Python
Variables
Functions
Conditional statements
Exception handling
Lambda functions
Modules and imports
Event-driven programming
Pandas
Reading Excel files
DataFrame manipulation
Data cleaning
Duplicate removal
Missing/blank data handling
Text column identification
String manipulation
Applying functions to columns
Exporting cleaned data
Tkinter
GUI development
Buttons
Entry fields
Checkboxes
Frames
Labels
File dialogs
Message boxes
StringVar
BooleanVar
GUI event handling
File Handling
File selection
Folder selection
File paths
File name extraction
Output path generation
Automated file naming

📂 Project Structure
Python-GUI-Excel-Data-Cleaning-Automation/
│
├── Python-Gui Based Automation.py
├── README.md
├── requirements.txt
│
├── Raw/
│   └── raw_sales_data_messy.xlsx
│
├── Output/
│   └── Cleaned_raw_sales_data_messy.xlsx
│
└── Screenshots/
    ├── application-interface.png
    ├── raw-data.png
    └── cleaned-data.png
⚙️ Installation
Step 1: Clone the Repository
git clone https://github.com/YOUR-USERNAME/python-gui-excel-data-cleaning-automation.git
Step 2: Navigate to the Project Folder
cd python-gui-excel-data-cleaning-automation
Step 3: Install Required Libraries
python -m pip install -r requirements.txt

Or install the libraries individually:

python -m pip install pandas openpyxl
▶️ How to Run

Run the Python file:

python "Python-Gui Based Automation.py"

The GUI application will open.

Then:

Click Browse and select an Excel file.
Select the cleaning operations you want to perform.
Select the destination output folder.
Click Clean Data.
The cleaned Excel file will be automatically generated in the selected folder.
📊 Example
Raw Data

The project includes a deliberately messy sample dataset containing:

Duplicate records
Blank rows
Leading spaces
Trailing spaces
Inconsistent capitalization
Mixed uppercase and lowercase text
Inconsistent text formatting

Example:

Customer Name     Region
--------------------------------
  rahul sharma    NORTH
PRIYA MEHTA       south
 Amit Kumar       East
RAHUL SHARMA      north
Cleaned Data

After applying the selected cleaning operations:

Customer Name     Region
--------------------------------
Rahul Sharma      North
Priya Mehta       South
Amit Kumar        East
🎯 Learning Outcomes

This project helped me gain practical experience in:

Python programming
Data cleaning and preprocessing
Pandas DataFrames
Excel automation
GUI application development
File and folder handling
Text data standardization
Duplicate and blank-row handling
Exception handling
Building user-friendly automation tools
Connecting a GUI with backend data-processing logic
🚀 Future Improvements

Possible future enhancements include:

Add a data preview before and after cleaning
Display cleaning statistics
Show the number of duplicate rows removed
Show the number of blank rows removed
Add CSV file support
Add more data-cleaning operations
Add column-specific cleaning options
Add automatic data-quality reports
Add logging functionality
Improve the GUI design
Package the application as a standalone .exe
💡 Why I Built This Project

The purpose of this project was to understand how Python can be used to automate repetitive data-processing tasks.

Data analysts frequently work with raw datasets that require cleaning before analysis. By automating common cleaning operations, this application demonstrates how Python can reduce repetitive manual work and improve the efficiency of data preparation.

👨‍💻 Author

Jatin

Aspiring Data Analyst | Python | SQL | Excel | Data Analytics

⭐ If You Find This Project Useful

Feel free to explore the repository, try the application with the sample dataset, and provide feedback.

If you find this project useful, consider giving the repository a ⭐.

🏷️ Tags

Python Pandas Tkinter Excel OpenPyXL Data Cleaning Data Analytics Automation Python Project Excel Automation Data Preprocessing


### One recommendation before you upload it

For your GitHub portfolio, I would **not upload only the `.py` file**. Include these four things:

1. **Your Python code**
2. **`requirements.txt`**
3. **The messy sample Excel file**
4. **2–3 screenshots of the application + before/after data**

That makes the repository look like a **complete portfolio project**, rather than a course exercise.
