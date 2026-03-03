python-project-management-analysis
│
├── data
│   ├── employee_data.csv
│   ├── project_data.csv
│   └── seniority_data.csv
│
├── notebooks
│   └── Final.ipynb
│
├── output
│   └── total_project_cost.csv
│
├── images
│   ├── dataframe_preview.png
│   └── analysis_results.png
│
├── README.md
├── requirements.txt
└── .gitignore
## Dataset Preview

### Employee Dataset
![Employee Data](images/dataframe_preview.png)

### Project Dataset
![Project Data](images/analysis_results.png)
## Analysis Output

The analysis calculates the total project cost handled by each employee.

| ID | First Name | Total Project Cost |
|----|-----------|-------------------|
| A001 | John | 3002000 |
| A002 | Alice | 2680000 |
| A003 | Tom | 5150000 |
| A004 | Nina | 9500000 |
| A005 | Amy | 600000 |
## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- ## Project Workflow

1. Created datasets and converted them into CSV files
2. Loaded datasets using Pandas
3. Cleaned missing values using running average
4. Split employee names into first and last names
5. Merged employee, project, and seniority datasets
6. Calculated bonus for completed projects
7. Adjusted designation levels based on project status
8. Calculated total project cost for each employee
