# Project 1: Standardized Test Analysis

### Overview

For our first project, we're going to take a look at aggregate SAT and ACT scores and participation rates in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to address our problem statement.

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.

### Problem Statement

We are a group of academia specialists, hired by institutions in the US to identify states with growth potential in private tuition to secure entry to College based on:
    1. ACT/SAT Subject scores

### Datasets

Listed below are the datasets included in the [`data`](../data/) folder for this project. 

* [`act_2017.csv`](../data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2018.csv`](../data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019.csv`](../data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`sat_2017.csv`](../data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](../data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](../data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))le


### Data Cleaning

In this project, we have merged all the data from SAT & ACT 2017 - 2019 into one dataframe in order to make sure the states in the SAT data and ACT data tally with each other.

### Analysis 1: ACT and SAT Subject Score

Based on the 2017 to 2019 ACT and SAT datasets, we calculate the SAT/ACT's average mean score for each year and we realised an overall decreasing trend in both SAT and ACT scores. This implies that there are room for improvement of the student's score for both SAT and ACT. There are potential for private tuition business for both SAT and ACT.

Now that we have identified that both SAT and ACT could be offered by potential private tuition centres, we can further break down into the subjects and narrow down to a few potential states to start off their business with. SAT includes only two subjects, Evidence-based Reading and Writing (EBRW) and Math, while ACT included subjects such as English, Reading, Math and Science. Based on the subjects, we will narrow it down to the top 5 least scored states for each subject for private tuition centres which only want to focus on a few subjects instead of all. Finally, we will also make recommendation for potential states for tuition centres which want to have a more well rounded tuition offered for all subjects. 

### Conclusion and Recommendation

In the analysis of the targeted states based on ACT and SAT subjects, we would recommend private tuition business to offer tuitions for a variety of subjects. This arrangement will take care of students who would want to have tuition for either a combination of subjects or just one subject. Tuition centres can also offer attractive tuition packages to attract students to sign up to their tuition packages. This allows a more well-rounded tuition centre, taking care of students with different needs and able to maximise their profit. Therefore, we would make our recommendation based on the least scored states for all subjects, be in ACT or SAT.

#### For ACT
Students generally score lower for English subject as compared to other subjects. This finding enables tuition centres to have a better decision on their allocation of resources. For example, they could hire more English teacher in order to keep up with the arrangement of have more English classes as compared to other subjects. For tuition centres who would like to to allocate equal amount of classes for all ACT subjects, Nevada, Mississippi and South Carolina could be the potential states to be targeted as they are in the top 5 least scored states for all 4 subjects. However, do note that Nevada's data might not be a good representation due to its location. It is the 9th-least densely populated state out of all the US states. Due to its low population, this might not be a good representation of its state's score. 

#### For SAT
Students generally score lower for Math than EBRW. Thus, for tuition centres who want to provide tuition for SAT, they can allocate more resources for Math subject as compared to EBRW. With our findings, we can conclude for tuition centres which want to have a more well rounded tuition for both subjects, District of Comlumbia, Delaware, Idaho and Michigan seems to be the potential states to start off with as they are the few states that scored the least for both subjects.

#### Recommendation
In order to further substantiate our conclusion, it is recommended to analyse the GDP per state and population for each state. GDP per state reflects the purchasing power of each state and this analyse will give private tuition business a rough gauge on their profit and how to price their tuition lessons or package such that it is competitive. Population is also another criteria to be considered, this allows private tuition businesses to gauge the number of potential student intakes and profit. 

Other possible datas to be analysed could be age distribution, government spending on education and test suitability based on students' capability for private tuition businesses to make better decision.

