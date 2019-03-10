# SECTION 1 : PROJECT TITLE
### MRCard Recommender System

# SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
With the income of working adults in singapore steadily rising over the years, many people are gaining access to credit cards, especially young working adults. The majority of adults nowadays own at least one or more credit cards, with many others planning to start using credit cards as well. Banks have also been actively coming up with more credit cards and trying and to get consumers to take them up. 

There can be many advantages in having a credit card. One advantage is that credit card users can earn benefits in terms of rebates, air miles, and rewards. This is usually the main draw for people to use credit cards. However, not every card is suitable for everyone. Each card has its own requirements and rates, and whether the user can earn the benefits from the card largely depends on their lifestyle and spending habits. With many credit cards available from the banks in Singapore, it can be a time-consuming task to pick up a suitable credit card, and many people simply get cards where their potential benefits are not maximised.

As a group of 5 young working professionals, we felt that this was a very relevant issue. Hence, we came up with the idea of designing a recommendation system to recommend the most suitable credit card or saving account based on the applicant's personal background, spending habits and personal preferences.

For this project, we first set out to perform knowledge acquisition by interviewing a subject matter expert, and also conducting a survey. To build the system, we decided to utilise the Django web framework, for its ease of integration with the front-end user interface (done with HTML), and the back-end rules engine (PyKnow) that we used to perform rule-based reasoning.

Our team learned a lot in the process of working on this project. We got the chance to apply techniques (like knowledge acquisition and rule-based reasoning) that we learned in our lectures and workshops in a viable business application scenario, and also picked up technical skills which would surely prove useful in the future course of our work.

# SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name | Student ID (MTech Applicable)| Work Items (Who Did What) | Email (Optional) |
| :---: | :---: | :---: | :---: |
| LI DUO  | A0195364W | Business idea generation, domain expert interview, reward rules implementation and project report | e0384995@u.nus.edu |
| LIM CHONG SENG HERMANN | A0195392U | Business idea generation, project report, project video and testing execution | e0385023@u.nus.edu |
| LU JIAHAO | A0091835Y | Business idea generation, UI design, domain expert interview, project report and testing execution | e0384293@u.nus.edu |
| YAM GUI PENG DAVID | A0195315A | Business idea generation, overall rules implementation, database and backend logic, overall integration and project report | e0384946@u.nus.edu |
| ZHAO YAZHI | A0195305E | Business idea generation, cashback rules implementation, survey result analysis, fuzzy logic implementation and project report | e0384936@u.nus.edu |

# SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO
Sudoku AI Solver

Note: It is not mandatory for every project member to appear in video presentation; Presentation by one project member is acceptable. More reference video presentations here

# SECTION 5 : USER GUIDE
[ 1 ] To run the system in any machine with anaconda 3 installed
$ git clone https://github.com/davidygp/IRS-MR-2019-01-19-IS1PT-GRP-MRCard
$ cd ./IRS-MR-2019-01-19-IS1PT-GRP-MRCard/SystemCode
$ source activate ./venv/MRCard-env
(MRCard-env) $ python manage.py runserver
Go to URL using web browser http://127.0.0.1:8000/
$ (MRCard-env) $ source deactivate

[ 2 ] To run the system in other/local machine: Install additional necessary libraries. This application works in python 3 only.
$ pip install anaconda 3 
$ git clone https://github.com/davidygp/IRS-MR-2019-01-19-IS1PT-GRP-MRCard
$ cd ./IRS-MR-2019-01-19-IS1PT-GRP-MRCard/SystemCode
$ source activate ./venv/MRCard-env
(MRCard-env) $ python manage.py runserver
Go to URL using web browser http://127.0.0.1:8000/
$ (MRCard-env) $ source deactivate

# SECTION 6 : PROJECT REPORT / PAPER
<Github File Link>  https://github.com/telescopeuser/Workshop-Project-Submission-Template/blob/master/ProjectReport/Project%20Report%20HDB-BTO.pdf

Recommended Sections for Project Report / Paper:

+ Executive Summary / Paper Abstract
+ Business Problem Background
+ Project Objectives & Success Measurements
+ Project Solution
+ Project Performance & Validation
+ Project Conclusions: Findings & Recommendation
+ List of Abbreviations
+ References

# SECTION 7 : MISCELLANEOUS
MRCard Survey Result.xlsx
+ Results of survey
+ Insights derived, which helped on features selection that are subsequently used in our system
