# bank-salaries
## First Problem: Bank salaries

Your client an American bank *Scrooge McDuck Inc.* based in Duckburg wants to know, if there exists a discrimination against minorities through different salaries. He provides you with a dataset containing next to the salaries of its employees information about their start salaries, years of education, gender, and an indicator of being part of a minority. As an expirienced data scientist you clearly know that OLS might help you here to understand the dependencies of the salary on different variables. Find out, if there might be a difference in salary depending on an employee's gender and/or minority affiliation. What role does the job category play?

[Bank salary data](https://drive.google.com/file/d/1JjsyxhLufGx6KH5PPJ6cBQJLQdLWGFny/view?usp=sharing)

### Data Description

- **SALARY**: Yearly salary in US-dollars
- **LOGSAL**: Logarithmised salary
- **EDUC**: Education in years
- **SALBEGIN**: Starting salary
- **LOGSALBEGIN**: Logarithmised starting salary
- **GENDER**: Gender of the employee (0: female, 1: male)
- **MINORITY**: Minority affiliation (0: non minority, 1: minority)
- **JOBCAT**: Job category, with levels (1: admin, 2: custodial and 3: manage).

**Hint**: Data is in ASCII-format. You will need to use a tab delimiter: `pd.read_csv('xm301bwa.asc', delimiter='\t')`

### Deliverables:

1. A well documented notebook.
2. A saved model.

## Installation of the environment
```bash
   pyenv local 3.9.8
   python -m venv .venv
   source .venv/bin/activate
   pip install --upgrade pip
   pip install -r requirements.txt
```
