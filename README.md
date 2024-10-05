
# College ROI analysis
This project aims to test the hypothesis that Rutgers University-Newark is consistently representative of the average U.S. college/university. We use real-world data from the U.S. Department of Education to analyze various characteristics of Rutgers-Newark and compare them with national averages.

## Null Hypothesis (H₀)
Rutgers University-Newark is consistently representative of the average U.S. college/university.

### Tools & Libraries Used
Python: Pandas, Numpy

Data Storage: CSV file stored in AWS S3 bucket

Analysis: Basic data cleaning, exploration, and statistical analysis

## Project Goals


### Data Cleaning:
Eliminate duplicate rows and remove non-operational colleges.
Create a subset of the dataset with the most relevant columns for analysis.
### Hypothesis Testing:
Analyze key columns to test if Rutgers-Newark is significantly different from the average U.S. college/university.
### Insight Generation:
Identify specific areas where Rutgers-Newark deviates from or aligns with national averages.
## Key Features of Data

Key Features of the Data
After reviewing the data dictionary, the following columns were identified as crucial for the analysis:

CURROPER: Indicates whether a college is currently operational. We only focus on operational colleges.

INSTNM: The name of the college, useful for final analysis.

OPEID: A unique identifier for each college, used to remove duplicates and streamline the data.

LOCALE: Describes the geographical setting (urban, rural, etc.), important for analyzing the college's environment.

CONTROL: Identifies if the institution is public, private non-profit, or private for-profit, which can affect tuition, admission rates, and more.

CCUGPROF: Generic profile of the college (two-year, four-year, etc.), providing a basis for comparison.

CCSIZSET: The size of the college, offering insights into whether Rutgers-Newark is larger or smaller than average.

ADM_RATE: Admission rate, helping to gauge the selectivity of the institution.

SAT_AVG: The average SAT score, which provides more context about the admission process.

TUITIONFEE_IN, TUITIONFEE_OUT: In-state and out-of-state tuition fees, giving an understanding of the cost of attending.

C150_4, C150_L4: Completion rates, measuring how many students complete their undergraduate degrees in the expected timeframe.


## Final Analysis
Upon analyzing the dataset, we found that Rutgers-Newark differs from the average U.S. college in several significant ways:

Key columns like CONTROL, CCUGPROF, CCSIZSET, TUITIONFEE_OUT, and C150_4 show that Rutgers-Newark is far from typical.
Out of 9 testable columns, Rutgers-Newark deviated in 5, which suggests that the null hypothesis is false.


## Conclusion
Rutgers-Newark is not representative of the average U.S. college in several important aspects, refuting the null hypothesis. This analysis provides a foundation for future comparisons with other institutions to determine if Rutgers-Newark offers a strong return on investment for prospective students.
