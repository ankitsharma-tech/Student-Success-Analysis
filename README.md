# 🎓 Student Success Analysis

## Final report: [report.pdf](./report.pdf)

## 📖 Project Overview

The main goal of this project was to create a comprehensive report explaining concepts of **statistical data analysis** applied to an existing dataset.

- The choice of statistical methods was flexible, as long as they were relevant and covered in the course curriculum.
- The report included test cases, either from the recommended list provided by faculty or created by team members.
- **R language** was used for data analysis and report generation.

Project evaluation was based on:

1. **Report quality**
2. **Oral examination** testing knowledge of theoretical concepts (e.g., when to use a test, test assumptions, and method details).

---

## 📊 Dataset

The dataset consists of survey responses and student grades in **mathematics** and **Portuguese** from two high schools.

Collecting this type of data is essential for analyzing and improving the quality of the education system.  
More details: [pdfs/dataset_documentation.pdf](./pdfs/dataset_documentation.pdf)

---

## 📂 Directory Structure

| Directory                     | Description                                        |
| ----------------------------- | -------------------------------------------------- |
| [auditorne](./auditorne/)     | Reference to existing problems and their solutions |
| [cheatsheets](./cheatsheets/) | Tidyverse cheat sheets in PDF format               |
| [pdfs](./pdfs/)               | Dataset and project descriptions                   |
| [src](./src/)                 | R Markdown source files and dataset                |

---

## ⚙️ Installation

### Windows

- Install [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
- Install [R](https://cran.r-project.org/bin/windows/base/)

### Linux

- Install [RStudio](https://www.rstudio.com/products/rstudio/download/#download)
- Install R and tidyverse dependencies:
  ```bash
  sudo apt-get install r-cran-curl r-cran-openssl r-cran-xml2 libxml2-dev
  ```

## 📦 R Packages Setup

1. Open **RStudio** → Open Project → `student-success-analysis.Rproj`
2. The file `student-success-analysis.Rmd` should open automatically
   - If not, navigate to it in the **Files** panel and double-click
3. Run the first code chunk (`Ctrl + Shift + Enter`) containing the `library` functions
4. A popup will prompt to install required packages → click **Yes**
5. Installation may take ~20 minutes

---

## 📝 Notes

**KS Test:**

- If _p = 1_ → data surely come from the same distribution
- If _p = 0_ → data come from different distributions

## 📋 To-Do

- [ ] Spellcheck the report
- [x] Write introduction to the problem
