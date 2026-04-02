# NYC-TEST-RESULTS
#  NYC Student Performance Analysis

##Project Overview
Every year, American high school students take the SAT—standardized tests designed to measure literacy, numeracy, and writing skills. The exam consists of three sections: **Reading, Math, and Writing**, each scored out of 800 points.

This project analyzes SAT performance across New York City (NYC) public schools to uncover patterns, trends, and insights that can support **education stakeholders, policymakers, and parents** in decision-making.

---

## Objectives
The analysis focuses on answering three key questions:

1. Which schools have the best overall SAT performance?  
2. Which borough has the highest average SAT scores?  
3. How do individual SAT sections (Reading, Math, Writing) compare across schools?  

---

## Tools & Technologies
- Python  
- pandas  
- matplotlib / seaborn  
- Jupyter Notebook  

## Dataset
- **File:** `schools.csv`  
- Contains SAT performance data for NYC public schools  
## Methodology
 ### 2. Exploratory Data Analysis (EDA)
- Examined score distributions  
- Compared performance across boroughs  
 ## 📈 Key Insights
- Identified top-performing schools based on total SAT scores  
- Highlighted boroughs with the strongest academic performance  
- Observed variations between Reading, Math, and Writing scores  
  ##finding

                                          school_name  average_math
88                              Stuyvesant High School           754
170                       Bronx High School of Science           714
93                 Staten Island Technical High School           711
365  Queens High School for the Sciences at York Co...           701
68   High School for Mathematics, Science, and Engi...           683
                      mean         std  count
borough                                      
Bronx          1202.724490  150.393901     98
Brooklyn       1230.256881  154.868427    109
Manhattan      1340.134831  230.294140     89
Queens         1345.478261  195.252899     69
Staten Island  1439.000000  222.303596     10
           average_SAT  std_SAT  num_schools
borough                                     
Manhattan      1340.13   230.29           89


### 1. Clone the repository
```bash
git clone https://github.com/VStanley04/NYC-TEST-RESULTS.git
