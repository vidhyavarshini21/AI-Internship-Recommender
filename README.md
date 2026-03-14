# AI-Internship-Recommender
AI-Powered Internship Recommendation System built with Flask, using user skills, education, location, and resume to suggest top internship opportunities.
AI-Based Internship Recommendation System 

 

Project Type: AI-Powered Recommendation System 

Team Name: Spotit  

Members: 

Shalini  

Vidhiya Varshini 

Yuvashri 

Sanofar 

 

Problem Statement: 

Many students and fresh graduates struggle to find internships that match their skills, qualification, and interests. Internship portals often contain hundreds of listings, making it difficult for users to identify the most suitable opportunities. 

As a result: 

Students apply to irrelevant internships. 

Recruiters receive mismatched applications. 

Candidates miss opportunities that match their capabilities. 

Therefore, an intelligent recommendation system is needed to help candidates quickly identify the most relevant internships. 

 

Objective: 

The objective of this project is to build a lightweight AI-based internship recommendation engine that suggests the top 3 internships to users based on their profile information. 

The system analyzes: 

Education qualification 

Technical skills 

Preferred sector 

Preferred location 

and recommends internships that best match these parameters. 

The system is designed to be: 

Simple and user-friendly 

Lightweight and fast 

Easily integrable into internship portals 

Accessible to students with minimal technical knowledge 

 

Proposed Solution: 

                      The proposed system consists of a web application built using Python Flask that recommends internships based on a rule-based scoring algorithm. 

The system performs the following tasks: 

Collects candidate details through a web interface. 

Processes internship data from a structured dataset. 

Matches candidate skills and preferences with internship requirements. 

Calculates a compatibility score. 

Returns the top 3 most suitable internships. 

 

System Architecture 

Frontend 

Technology: HTML, CSS, JavaScript 

Features: 

Simple and intuitive interface. 

Input form for candidate details. 

Displays internship recommendations clearly. 

Accessible on both desktop and mobile browsers. 

Backend 

Technology: 

Flask 

Pandas 

NumPy 

Responsibilities: 

Handles user requests. 

Processes internship data. 

Executes recommendation logic. 

Returns results through REST API. 

 

Recommendation Engine: 

Phase 1 – Rule-Based Scoring 

          The system assigns scores to internships based on matching parameters. 

 

Scoring criteria: 

Parameter 

 

Score 

 

Skill Match 

 

+15 per skill 

 

Location Match 

 

+10 

Sector Match 

 

+5 

Skill Match Percentage Bonus 

 

+10 

Internships are ranked based on the final score, and the top 3 results are recommended. 

 

Phase 2 – Future Enhancement 

Future improvements may include: 

Machine learning recommendation models 

Collaborative filtering 

Resume-based skill extraction 

AI-based skill gap analysis 

Data Sources 

Internship Dataset 

A structured CSV dataset is used containing: 

Internship title 

Required skills 

Education requirement 

Sector 

Location 

Stipend 

 

Candidate Data 

User inputs collected through the web interface: 

Qualification 

Skills 

Preferred sector 

Preferred location 

 

Workflow Process 

User opens the internship recommendation web application. 

Candidate enters profile details such as qualification, skills, sector interest, and preferred location. 

The system retrieves internship data from the dataset. 

Data preprocessing ensures consistent formatting. 

The recommendation engine evaluates each internship using the scoring algorithm. 

Internships are ranked according to the calculated score. 

The top 3 internships are returned as recommendations. 

Results are displayed to the user on the interface. 

Flow chart: 

 

Key Features 

Personalized internship recommendations. 

Score-based ranking system. 

Skill matching and filtering. 

Location and sector preference matching. 

Lightweight backend using Flask. 

Fast response using structured dataset. 

 

Challenges and Solutions 

Challenges 
Solution 
Implemented scoring-based filtering 
Large number of internship listings 

 

Data inconsistencies in dataset 
Applied preprocessing and cleaning 
Skill mismatch between candidates and internships 
Skill validation using master skill list 
Need for lightweight system
Rule-based scoring instead of heavy ML models 

 

 

Impact and Benefits 

Helps students find internships relevant to their skills. 

Reduces application mismatch. 

Improves internship discovery efficiency. 

Provides quick and personalized recommendations. 

Can be integrated into educational or internship portals. 

 

Future Scope 

Integration with internship portals. 

Resume upload and automatic skill extraction. 

AI-based recommendation models. 

Multi-language support. 

Real-time internship database integration. 

 

References 

Job Recommendation Systems – Research Review 

Data Mining Techniques in Job Recommendation Systems 

Internship and Job Matching Algorithms in AI Systems
