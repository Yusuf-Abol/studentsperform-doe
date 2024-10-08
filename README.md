# 2^3 Factorial Experiments on Students' Performance

### -- Project Status: [Active, On-Hold, Completed]
## Project intro/objective
Academic success affects a child's self esteem and motivations. It can also be an early indicator of a child's pursuit for higher education. In Nigeria, most parents are of the opinion that private secondary schools are a better choice for their child's academic development than the public ones. Over the years, this situation has drastically increased enrollment into the private schools.


Using a 2^3 full factorial design , this project aims to investigate the effects of School, Gender, and Specialization on students' performance

### Methods Used

* Full Factorial Experiment 

* Data Visualization

* Analysis of Variance (ANOVA) 

* Hypothesis Testing

### Technologies

* Python
* Excel
* Pandas, pyDOE2, Statmodels, & Math
* JupyterLab

## Project Description
The WAEC results of 140  students (70F, 70M) from 2 schools were used for this project. Performance was gauged by coding the grades in Maths & English language using 9-point grading scale; A1 to F9 (A1=8, B2=7, B3=6, C4=5, C5=4, C6=3, D7=2, E8=1, F9=0). The data was analyzed using main/interaction effect plots, full factorial model with 3 factors, ANOVA table and Hypothesis testing.

## Dataset 
### Source 
This study utilized a confidential dataset provided by two secondary schools in Nigeria. The dataset contained the West African Examinations Council results of secondary school students, collected over two academic years. The schools wished to remain anonymous to maintain confidentiality.
### Attributes

Target/Response Variables

- SCORE (integer): Joint performance (derived from MATH + ENG)
- MATH (integer): Mathematics exam grade
- ENG (integer): English language exam grade


Predictor/Explanatory Variables

- SCH (categorical): School type
    - -1: Public school
    - 1: Private school
- GNDR (categorical): Student's gender
    - -1: Female
    - 1: Male
- SPEC (categorical): Student's specialization/field of study
    - -1: Humanities
    - 1: Science

## Needs of this project
* data scientist/analyst
* experimenter looking for information with smallest runs at low cost
* data exploration/inferential statistics
* statistical analysis

## Key Findings

* In the maths + english exam, the private school had a positively large effect on the students' performance. Although, the students'
gender or specialization (humanities to science) had no signficant influence on their test score regardless of school type.

* Meanwhile in the maths exam, the combination effect of School and Specialization had significant influence on the students' performance.

### Threats to the Validity of this Experiment

* There was no randomization in the selection of the two participating schools.

* Cases of exam malpractice or cheating might have influenced the results.

* The label "Humanities" is a combination of two classes: the "Commercial" and "Arts" classes.

* The data has uneven distribution of students in Science (=81) and Humanities(=59)

## References
[1]  Marcel Butschle, Example of a Full Factorial Design in Python https://www.experimentaldesignhub.com

[2] Douglas C. Montgomery (2012) Design and Analysis of Experiments, Arizona State University

[3] Glewe, P. (2002) Schools and skills in developing countries: Education policies and Socio-Economical Outcomes. Journal of Economics Literature

[4] Farooq, M.S., Shafiq, M. and Berhanu, G (2011). Factors Affecting Students' Quality of Academic Performance; A Case Study of Secondary School




