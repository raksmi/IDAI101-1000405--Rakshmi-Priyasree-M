# IDAI101-1000405--Rakshmi-Priyasree-M
AI-Based Smart Solutions: Designing Chatbots for Real-World Challenges: 
Scenario 2: Smart Campus Assistant: Navigating Life on Campus with AI
JVNOVA: Smart Campus Assistant Chatbot
Course Code: IDAI101
CRS Name: Artificial Intelligence
School Name: Jain Vidyalaya
Student Name: M. Rakshmi Priyasree
Candidate Registration Number: 1000405

Project Overview:

JVNOVA is an AI-powered Smart Campus Assistant Chatbot developed using Google Dialogflow as part of the IBCP Artificial Intelligence course.
The chatbot assists students, parents, and visitors with instant guidance about transportation, office timings, admissions, and campus navigation — acting as a virtual campus guide available 24/7.

-> Objective
To simplify access to campus-related information.
To reduce confusion among visitors and students.
To make campus communication faster and more efficient using AI.

-> Target Users
New Students
Parents & Visitors
Faculty and Administrative Staff

-> Architecture & Design
1 mega bot- 4 sub agents
Total Intents: 19
Total Entities: 6
Default Welcome & Fallback Intents: Enabled
Slot Filling & Parameters: Used for office timings, admissions, and navigation queries.

-> Sub-Agent Breakdown
Transportation Bot- 1 intent-	@mode(entity)
Office Timing Bot-	3 intents- 	@office, @day_type (entity)
Admission Bot-	5 intents-	@class(eentity)
Campus Navigation Bot-	10 intents-	@building_name, @department(entity)

-> Detailed description
Transportation Bot:
               - 
