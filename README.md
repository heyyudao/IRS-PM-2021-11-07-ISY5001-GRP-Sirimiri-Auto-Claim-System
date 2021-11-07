## SECTION 1 : Sirimiri Auto Claim System

---

## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT

Sirimiri Private Limited is a newly established international Food & Beverages Services company based in Singapore. The company aims to bring the best quality food across the globe to Singaporeans. The company's employees are constantly travelling to different countries to source the best quality food products. Hence, many expenses are spent overseas, be it taxis, food expenses, hotel accommodations etc. As Sirimiri Private Limited's business expanded, the company's claiming process had become a hassle to the management team. Therefore, the CEO of Sirimiri Private Limited has decided to look into Artificial Intelligence and automation to see if there is an intelligent solution for this. 

Sirimiri Private Limited have approached Yudao and Engkoon. They are students of NUS ISS undertaking the Graduate Certificate in Intelligent Reasoning Systems to develop an intelligent application to help the company automate their claiming process. Sirimiri Private Limited is looking for a fast rule-based automation setup built on a readily available platform, so its employees can claim their expenses anywhere around the globe. 

The solution proposed by Yudao and Engkoon is a chatbot built on the most popular instant message platform, i.e., Whatsapp. First, the chatbot can retrieve employee information through conversation using Dialogflow, a natural language understanding platform. Then, validate the claim amount using built-in OCR capabilities. Finally, the chatbot will auto-approve or reject a claim based on a user-defined rule-based system created using jBPM, an open-source workflow engine written in Java that can execute business processes. All the setups are then deployed on Amazon Elastic Compute Cloud to allow the employee to claim their expenses anytime in the day.

---

## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | 
| HE YUDAO     | SXXXX308J | Report / WhatsApp Chatbot / OCR / Fraud Detection | 
| LEE ENG KOON | SXXXX024A | Report / jBPM development / OCR | 


---

## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

[![Sudoku AI Solver](http://img.youtube.com/vi/-AiYLUjP6o8/0.jpg)](https://youtu.be/-AiYLUjP6o8 "Sudoku AI Solver")

Note: It is not mandatory for every project member to appear in video presentation; Presentation by one project member is acceptable. 
More reference video presentations [here](https://telescopeuser.wordpress.com/2018/03/31/master-of-technology-solution-know-how-video-index-2/ "video presentations")

---

## SECTION 5 : USER GUIDE

`Refer to appendix <Installation & User Guide> in project report at Github Folder: ProjectReport`

### [ 1 ] To run the system using iss-vm

> download pre-built virtual machine from http://bit.ly/iss-vm

> start iss-vm

> open terminal in iss-vm

> $ git clone https://github.com/telescopeuser/Workshop-Project-Submission-Template.git

> $ source activate iss-env-py2

> (iss-env-py2) $ cd Workshop-Project-Submission-Template/SystemCode/clips

> (iss-env-py2) $ python app.py

> **Go to URL using web browser** http://0.0.0.0:5000 or http://127.0.0.1:5000

### [ 2 ] To run the system in other/local machine:
### Install additional necessary libraries. This application works in python 2 only.

> $ sudo apt-get install python-clips clips build-essential libssl-dev libffi-dev python-dev python-pip

> $ pip install pyclips flask flask-socketio eventlet simplejson pandas

---
## SECTION 6 : PROJECT REPORT / PAPER

`Refer to project report at Github Folder: ProjectReport`

**Recommended Sections for Project Report / Paper:**
- Executive Summary / Paper Abstract
- Sponsor Company Introduction (if applicable)
- Business Problem Background
- Market Research
- Project Objectives & Success Measurements
- Project Solution (To detail domain modelling & system design.)
- Project Implementation (To detail system development & testing approach.)
- Project Performance & Validation (To prove project objectives are met.)
- Project Conclusions: Findings & Recommendation
- Appendix of report: Project Proposal
- Appendix of report: Mapped System Functionalities against knowledge, techniques and skills of modular courses: MR, RS, CGS
- Appendix of report: Installation and User Guide
- Appendix of report: 1-2 pages individual project report per project member, including: Individual reflection of project journey: (1) personal contribution to group project (2) what learnt is most useful for you (3) how you can apply the knowledge and skills in other situations or your workplaces
- Appendix of report: List of Abbreviations (if applicable)
- Appendix of report: References (if applicable)

---
## SECTION 7 : MISCELLANEOUS

`Refer to Github Folder: Miscellaneous`

### HDB_BTO_SURVEY.xlsx
* Results of survey
* Insights derived, which were subsequently used in our system

---

### <<<<<<<<<<<<<<<<<<<< End of Template >>>>>>>>>>>>>>>>>>>>

---

**This [Machine Reasoning (MR)](https://www.iss.nus.edu.sg/executive-education/course/detail/machine-reasoning "Machine Reasoning") course is part of the Analytics and Intelligent Systems and Graduate Certificate in [Intelligent Reasoning Systems (IRS)](https://www.iss.nus.edu.sg/stackable-certificate-programmes/intelligent-systems "Intelligent Reasoning Systems") series offered by [NUS-ISS](https://www.iss.nus.edu.sg "Institute of Systems Science, National University of Singapore").**

**Lecturer: [GU Zhan (Sam)](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan "GU Zhan (Sam)")**

[![alt text](https://www.iss.nus.edu.sg/images/default-source/About-Us/7.6.1-teaching-staff/sam-website.tmb-.png "Let's check Sam' profile page")](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan)

**zhan.gu@nus.edu.sg**
