# Women in Politics
## Exploring Factors Associated with Women's Representation in National Legislative Bodies
**Natasha Halfin**  
**DATA 512 - Human Centered Data Science**  
**University of Washington**  
**December 2020**  

*This repository reflects my final project analysis for the DATA 512 Human Centered Data Science course (Autumn 2020, University of Washington, Master of Science in Data Science program).*

### Abstract
 Globally, women account for barely one quarter of the representation in parliamentary/legislative bodies, and as of 2019, the [U.S. ranked 75th out of 193 world countries](https://www.cnbc.com/2019/03/04/the-us-ranks-75th-in-womens-representation-in-government.html) in its share of women in goverment. However, research shows that women perform just as well as men in elections, and the socio-economic benefits of greater representation of women are well-documented. Therefore, the low number of women in govemerment may be attributed to systemic obstacles that hinder women from pursuing a path in politics. In my analysis, I explored the relationship between women's representation in politics and gender parity indicators in the workplace, law, and society. My research question and hypothesis were as follows:    

**Research Question: What factors are associated with countries with greater representation of women in politics?**  

**Hypothesis: Countries with better performance across key gender parity indicators are more likely to have greater representation of women in politics.**

To answer my research question, I utilized data from the OECD and performed a descriptive correlative analysis, as well as a predictive analysis via linear regression models. I discovered that all of the gender parity indicators demonstrated weak correlations (under 0.5) with the rate of political representation, and the models I constructed 

### Background
Globally, women account for barely one quarter of the representation in parliamentary/legislative bodies, and as of 2019, the [U.S. ranked 75th out of 193 world countries](https://www.cnbc.com/2019/03/04/the-us-ranks-75th-in-womens-representation-in-government.html) on the share of women in goverment. However, research shows that women perform just as well as men in elections, and the socio-economic benefits of greater female representation are well-documented. Therefore, the low number of women in govemerment may be attributed to systemic obstacles that hinder women from pursuing a path in politics. This project seeks to explore how key indicators of gender parity, like education, earnings, representation in the commercial sector, and maternity leave, may be associated with female representation in political bodies. For additional details and sources on background work, please refer to the [project proposal](https://github.com/nhalfi/data-512-final/blob/main/final_project.ipynb) in this repository.

### Dependencies
[Python, Jupyter notebook, etc]

### Data Source  
I leveraged data from the OECD website database: https://stats.oecd.org/index.aspx?queryid=54760#

### Data Dictionary

Definitions from OECD and https://www.genderindex.org/methodology/

Column | Definition 
:--- | :---
Share of Women in Parliament | Percentage of women who make up a country's parliamentary body
Female share of seats on boards of the largest publicly listed companies | Proportion of seats held by women on boards for companies covered by the MSCI ACWI index -- an index of around 2,400 large- and mid-cap firms from developed and emerging countries. 'Board members' refers to either the board of directors for companies in a unitary system, or the supervisory board in the case of a company in a two-tier system, with management and audit boards ommitted.
Share of female managers | Percentage of all managers who are women
Length of Maternity Leave | number of weeks of job-protected leave available for mothers just before and after childbirth.
Access to Financial Services Law | Whether women and men have the same legal rights to open a bank account and obtain credit in a formal financial institution. Values range from 0 to 1 on a 0.25 pt scale. 0 indicates Women and men have the same rights to open a bank account and obtain credit at a formal financial institution, without legal exceptions regarding some groups of women. Customary, religious and traditional laws or practices do not discriminate against women’s above legal rights. 0 indicates that women have the same rights as men  and customs do not discriminate against women’s above legal rights. 1 indicates that women do not have the same rights as men in this regard.
Divorce Law | Whether women and men have the same legal rights to initiate divorce and have the same requirements for divorce or annulment. Values range from 0 to 1 on a 0.25 pt scale. 0 indicates that women have the same rights to initiate divorce as men, without negative repercussions on their parental authority. Customs do not discriminate against women’s rights regarding divorce or parental authority after divorce. 1 indicates that women do not have the same rights as men with respect to initiating and finalizing divorce and experience restricted parental rights after divorce.
Reproductive Autonomy Law | Whether the legal framework protects women’s reproductive health and rights. Values range from 0 to 1 on a 0.25 pt scale. 0 indicates that the country's laws protect women’s reproductive health and rights in case of unwanted pregnancy, without any justifications. 1 indicates that these rights are not protected in the case of unwanted pregnancy.  
Household Responsibilities Attitudes | Percentage of the population agreeing or agreeing strongly that "when a mother works for pay, the children suffer".
Violence Against Women Practices | Percentage of ever-partnered women who ever suffered intimate partner physical and/or sexual violence.


