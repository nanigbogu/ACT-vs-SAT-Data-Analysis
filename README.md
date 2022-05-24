# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Overview

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math totaling 154 questions with an alotted 180 minutes to complete and a score range of 1 to 36 ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science totaling 215 questions with an alotted 175 minutes to complete and a score range of 400 to 1600 ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites:
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)


### Problem Statement

Many high school students know which college they’d like to consider, but rarely know whether to take the SAT or ACT when applying to these colleges or many just choose to default to the exam their school offers. We will explore the participation rates and average ACT and SAT scores broken down by region.

---

### Datasets

#### Raw Data

* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))

#### Final Datasets

* [`act_sat_2017.csv`](./data/cact_sat_2017.csv)
* [`act_sat_2018.csv`](./data/cact_sat_2018.csv)
* [`act_sat_2019.csv`](./data/cact_sat_2019.csv)

---

### Data Dictionary

|Feature|Type|Datasets|Description|
|---|---|---|---|
|**act_part**|*float*|act_sat_17 & act_sat_18 & act_sat_19|Participation rates for ACT by state| 
|**act_comp**|*float*|act_sat_17 & act_sat_18 & act_sat_19|Average composite score for ACT by state| 
|**sat_part**|*float*|act_sat_17 & act_sat_18 & act_sat_19|Participation rates for SAT by state| 
|**sat_tot**|*integer*|act_sat_17 & act_sat_18 & act_sat_19|Average composite score for SAT by state| 

---

## Data Analysis

The data shows a strong negative correlation between participation rates and standardized testing scores. 

---

## Conclusions and Recommendations

**Should high school students take the SAT or ACT?**

It depends! It depends!  One test may better align with their personal strengths and level of knowledge. Although some regions show a strong affinity to one test, it does not correlate with how well they will perform. In fact, the lower the participation of the standardized test, the better that region performs on the exam. This could be for many reasons, one of which may be that those taking the "less popular" exam, are taking it because they took a practice exam or did research on the difference and determined whether they would be more successful at either or took both just in case. 

I recommend that each student take the pre-exam for both the ACT and SAT so that they can determine which test they feel more equipped to take come the official exam. 