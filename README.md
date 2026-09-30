# Messy Employee Data Cleaning

A beginner-friendly pandas project that loads, inspects, cleans, audits, and exports a messy employee CSV dataset.

Project reference: https://roadmap.sh/projects/clean-csv

## Project Files

- `clean.ipynb` - Main Jupyter notebook containing the cleaning workflow.
- `Messy_Employee_dataset.csv` - Original input dataset.
- `Messy_Employee_dataset_cleaned.csv` - Cleaned output produced by the notebook.
- `project description.md` - Project requirements and learning goals.

## Requirements

- Python 3
- VS Code with the Jupyter and Python extensions, or another Jupyter environment
- pandas
- numpy

Install the Python packages with:

```powershell
python -m pip install pandas numpy
```

## Open and Use the Project

1. Open the project folder in VS Code.
2. Open `clean.ipynb`.
3. Select a Python 3 kernel when VS Code prompts you.
4. Run the notebook cells from top to bottom.
5. The notebook will:
   - Load the CSV with UTF-8 encoding and comma separation.
   - Apply explicit column data types.
   - Convert `Join_Date` to dates.
   - Standardize categorical values.
   - Fill missing age and salary values.
   - Check for duplicate records.
   - Export and audit the cleaned dataset.
6. Open `Messy_Employee_dataset_cleaned.csv` to view the result.

You can also run the notebook with Jupyter from the project folder:

```powershell
jupyter notebook clean.ipynb
```

## Output

The final audit checks the exported file's shape, columns, missing values, duplicate records, and categorical whitespace. The cleaned file is written as:

```text
Messy_Employee_dataset_cleaned.csv
```
