# R Data Science Assignments

Assignments for the R for Data Science course (MSc Big Data Analytics, AUCA).

**Author:** Moise Tuyizere

## Assignment 1: Installing packages and importing data

Installs R packages, imports data from seven different sources, and uses the packages to describe each dataset.

| File | Source | Package |
|---|---|---|
| students.txt | Text file | base R |
| purchase_orders.csv | CSV file | base R |
| store_stock.xlsx | Excel | readxl |
| staff_survey.sav | SPSS | haven |
| staff_survey.dta | Stata | haven |
| staff_survey.xpt | SAS | haven |
| procurement.sqlite | Database (SQLite) | DBI, RSQLite |

* [Assignment1.md](Assignment1/Assignment1.md) shows the results and graphs.
* [Assignment1.Rmd](Assignment1/Assignment1.Rmd) is the R Markdown code.

### How to run

1. Download or clone this repository.
2. Open `Assignment1/Assignment1.Rmd` in RStudio.
3. Change `data_folder` to the folder where you saved the files.
4. Install the packages once: `install.packages(c("readxl", "haven", "DBI", "RSQLite"))`
5. Click **Knit**.
