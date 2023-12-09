# LinkedIn Jobs Machine Learning Dataset

[![Kaggle Dataset](https://img.shields.io/badge/Kaggle-Dataset-informational)](https://www.kaggle.com/datasets/adampq/linkedin-jobs-machine-learning-data-set)

## Overview

This repository contains the LinkedIn Jobs Machine Learning Dataset, a comprehensive dataset derived from LinkedIn job postings. The dataset includes information about companies, job titles, salaries, and various other attributes, making it a valuable resource for exploring trends and patterns in the job market.

## Dataset Details

- **Size:** 40Mo
- **Columns:**
- Co_Nm / Company Name, dType Object
- Co_Pg_Lstd / Company Page Listed, dType Bool
- Emp_Cnt / Company Employee Count, dType int64
- Flw_Cnt / Company Follower Count, dType int64
- Job_Ttl / Job Title, dType Object
- Job_Desc / Job Description, dtype Object
- Is_Supvsr / Is Post a Supervisor Position (Calculated), dType Bool
- max_sal / Maximum Salary, dtype Float64
- med_sal / Median Salary, dtype Float64
- min_sal / Minimum Salary, dtype Float64
- py_prd / Pay Period, dtype Category {Not Listed, YEARLY, HOURLY, MONTHLY, Unpaid, WEEKLY, ONCE}
- py_lstd / Pay Listed (Calculated), dtype Bool 
- wrk_typ / Work Type, dtype Category {Full-time, Contract, Part-time, Temporary, Internship, Other, Volunteer}
- loc / Job Location, dtype Object
- st_code / Job State Code (Calculated), dtype Object
- is_remote / Is Job Remote (Calculated), dtype Bool
- views / Number of Posting Views, dtype int64
- app_typ / Application Type, dtype Category {Offsite Apply, SimpleOnSiteApply, ComplexOnSiteApply}
- app_is_off / Is Application Offsite (Calculated), dtype Bool
- xp_lvl / Experience Level, dtype Category {Mid-Senior level, Not Listed, Entry level, Associate, Director, Internship, Executive}
- domain / Posting Domain, dtype Object
- has_post_domain / Has Posting Domain (Calculated), dtype Bool
- is_sponsored / Is Sponsored, dtype Bool
- base_comp / Has Base Compensation, dtype Bool
- **Source:** Kaggle

## Project Overview

In this project, we conducted a detailed analysis of the LinkedIn Jobs dataset, aiming to extract insights into various aspects of job postings. The analysis covers data cleaning, salary exploration, and marketing insights, providing a comprehensive view of the job market landscape.

## Getting Started

To get started with this dataset, follow these steps:

1. [Download the dataset from Kaggle](https://www.kaggle.com/datasets/adampq/linkedin-jobs-machine-learning-data-set).
2. Clone this repository to your local machine.
3. Explore the dataset using the provided Jupyter notebooks.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

---

**Happy Exploring!**

Youssef Ben Salem
