# Women in Politics
## Exploring Factors Associated with Women's Representation in National Legislative Bodies
**Natasha Halfin**  
**DATA 512 - Human Centered Data Science**  
**University of Washington**  
**December 2020**  

*This repository reflects my final project analysis for the DATA 512 Human Centered Data Science course (Autumn 2020, University of Washington, Master of Science in Data Science program).*

### Abstract
 Globally, women account for barely one quarter of the representation in parliamentary/legislative bodies, and as of 2019, the [U.S. ranked 75th out of 193 world countries](https://www.cnbc.com/2019/03/04/the-us-ranks-75th-in-womens-representation-in-government.html) in its share of women in government. However, [research shows that women perform just as well as men in elections](https://carnegieendowment.org/2018/02/20/tackling-women-s-underrepresentation-in-u.s.-politics-comparative-perspectives-from-europe-pub-75315), and the socio-economic benefits of greater representation of women are well-documented. Therefore, the low number of women in government may be attributed to systemic obstacles that hinder women from pursuing a path in politics. In my analysis, I explored the relationship between women's representation in politics and gender parity indicators in the workplace, law, and society. My research question and hypothesis were as follows:    

**Research Question: What factors are associated with countries with greater representation of women in politics?**  

**Hypothesis: Countries with better performance across key gender parity indicators are more likely to have greater representation of women in politics.**

To answer my research question, I utilized OECD data and performed a descriptive correlative analysis, as well as a predictive analysis via linear regression models. I was unable to support my hypothesis given that the included gender parity indicators demonstrated weak correlations (under 0.5) with the rate of political representation, and the models I constructed did not predict well (R-squared of below 0.3 and MAE of roughly 9 percentage points). However, further research is needed to validate the relationship between gender parity indicators and women’s political representation.

**To see the complete analysis, please refer to this [Jupyter notebook](https://nbviewer.jupyter.org/github/nhalfi/Women-in-Politics/blob/main/FinalProjectAnalysis.ipynb).**

### Repository Guidance
In addition to the main analysis notebook linked above, I've also included:
* A [Data folder](https://github.com/nhalfi/Women-in-Politics/tree/main/Data). This contains two subfolders; one with the raw data that I downloaded from the OECD site, and another with the transformed datasets that I generated through the data cleaning steps in the Jupyter notebook.
* A [Visualizations folder](https://github.com/nhalfi/Women-in-Politics/tree/main/Visualizations). This contains two subfolders; one with plots from the descriptive analysis portion, and the other with plots generated from the predictive analysis section.

### Data Source  
I leveraged the following sources from the OECD website database:  
* [Gender, Institutions and Development Database (GID-DB) 2014](https://stats.oecd.org/Index.aspx?DataSetCode=GIDDB2014)
* [Gender, Institutions and Development Database (GID-DB) 2019](https://stats.oecd.org/Index.aspx?DataSetCode=GIDDB2019)
* [Employment dataset](https://stats.oecd.org/Index.aspx?DataSetCode=GENDER_EMP)


### Data Dictionary

The following definitions are from the [OECD documentation](https://www.genderindex.org/methodology/).  

[**2014 Dataset**](https://github.com/nhalfi/Women-in-Politics/blob/main/Data/Transformed%20Data/WIP2014.csv)
Column | Definition 
:--- | :---
Female Share of Board Seats | Proportion of seats held by women on boards for companies covered by the MSCI ACWI index -- an index of around 2,400 large- and mid-cap firms from developed and emerging countries. 'Board members' refers to either the board of directors for companies in a unitary system, or the supervisory board in the case of a company in a two-tier system, with management and audit boards ommitted.
Female Share of Managers | Percentage of all managers who are women.
Length of Maternity Leave | Number of weeks of job-protected leave available for mothers just before and after childbirth.
Median Gender Wage Gap | The difference between male and female median wages divided by the male median wages.
Political Representation | Percentage of women in the total number of representatives of the lower or single House of the Parliament.

[**2019 Dataset**](https://github.com/nhalfi/Women-in-Politics/blob/main/Data/Transformed%20Data/WIP2019.csv)  
Column | Definition   
:--- | :---  
Access to Financial Services | Whether women and men have the same legal rights to open a bank account and obtain credit in a formal financial institution. Values range from 0 to 1 on a 0.25 pt scale. 0 indicates Women and men have the same rights to open a bank account and obtain credit at a formal financial institution, without legal exceptions regarding some groups of women. Customary, religious and traditional laws or practices do not discriminate against women’s above legal rights. 0 indicates that women have the same rights as men  and customs do not discriminate against women’s above legal rights. 1 indicates that women do not have the same rights as men in this regard.
Divorce | Whether women and men have the same legal rights to initiate divorce and have the same requirements for divorce or annulment. Values range from 0 to 1 on a 0.25 pt scale. 0 indicates that women have the same rights to initiate divorce as men, without negative repercussions on their parental authority. Customs do not discriminate against women’s rights regarding divorce or parental authority after divorce. 1 indicates that women do not have the same rights as men with respect to initiating and finalizing divorce and experience restricted parental rights after divorce.
Household Responsibilities Attitudes | Percentage of the population agreeing or agreeing strongly that "when a mother works for pay, the children suffer".
Political Representation | Percentage of women in the total number of representatives of the lower or single House of the Parliament.
Reproductive Autonomy | Whether the legal framework protects women’s reproductive health and rights. Values range from 0 to 1 on a 0.25 pt scale. 0 indicates that the country's laws protect women’s reproductive health and rights in case of unwanted pregnancy, without any justifications. 1 indicates that these rights are not protected in the case of unwanted pregnancy.  
Violence Against Women | Percentage of ever-partnered women who ever suffered intimate partner physical and/or sexual violence.

### Dependencies
To reproduce the results obtained in this analysis, you will need:  
* A recent version of [Python](https://www.python.org/) installed (3.7 or higher)
* The following packages installed:
  + Matplotlib
  + Numpy
   + Pandas
   + Pandas_profiling
  + Seaborn
  + Sklearn
  + Statsmodels
* An IDE to run Jupyter notebooks in ([I like to use Visual Studio Code](https://code.visualstudio.com/))

### License and Terms of Use
Please refer to the following [license](https://github.com/nhalfi/Women-in-Politics/blob/main/LICENSE).  
Also, you can find the OECD's terms and conditions for use of data [here](http://www.oecd.org/termsandconditions/).
