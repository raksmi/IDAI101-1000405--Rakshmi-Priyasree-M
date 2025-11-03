# IDAI101-1000405-Rakshmi-Priyasree-M
AI-Based Smart Solutions: Designing Chatbots for Real-World Challenges: 
Scenario 2: Smart Campus Assistant: Navigating Life on Campus with AI
JVNOVA: Smart Campus Assistant Chatbot
Course Code: IDAI101
CRS Name: Artificial Intelligence
School Name: Jain Vidyalaya
Student Name: M. Rakshmi Priyasree
Candidate Registration Number: 1000405
Link for the chatbot: https://raksmi.github.io/IDAI101-1000405--Rakshmi-Priyasree-M/

Project Overview:

JVNOVA is an AI-powered Smart Campus Assistant Chatbot developed using Google Dialogflow as part of the IBCP Artificial Intelligence course.
The chatbot assists students, parents, and visitors with instant guidance about transportation, office timings, admissions, and campus navigation — acting as a virtual campus guide available 24/7.

JvNova is a Mega agent made up of 4 sub agents, I choose to create a Mega agent as it will be essay to make upcoming changes and manage intents and enities without mess

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

-->Transportation Bot

 Intent_Name: mode
 Purpose: Provides details about available transport modes (bus, van, cab, etc.).
 Example Questions: - Does school provide bus facilities?
                    - What are the transportation available?
                    - can i get the bus route

-->Office Timing Bot

 Intent_Name: Reception
 Purpose: Provides working hours for the Administrative Office on weekdays and weekends.
 Example Questions: - is school open tomorrow?
                    - can i come to reception today?
                    -is the office open tomorrow?

 Intent_Name: Appointment
 Purpose: Shows appointment procedures
 Example Questions: - can i meet principal today?
                    - Shall i come to meet admin tomorrow?
                    - is principal available today?

 Intent_Name: sun
 Purpose: Provides information about if the school is open on sundays or not
 Example Questions: - tomorrow is sunday, is the school open?
                    - Is it open on sunday?
                    - Is the school open on sunday?

-->Admission Bot

 Intent_Name: class 11 admission
 Purpose: provides data about courses available for grade 11
 Example Questions: - is admission open for grade 11?
                    - What are the courses available for class 11?
                    - admission for class 11?

 Intent_Name: Kindergarten
 Purpose: Provides steps to get a form for kindergarten admission
 Example Questions: - procedure to get admission for kindergarten?
                    - Admission  for LKG?
                    - is admission for kindergarten open?

 Intent_Name: primary school
 Purpose: Provides steps to get a form for primary school admission
  Example Questions: - procedure to get admission for primary?
                    - Admission  for class 5?
                    - is admission for primary open?

 Intent_Name: secondary schl
 Purpose: Provides steps to get a form for secondary admission admission

-->Campus Navigation Bot

 Intent_Name: Admin block
 Purpose: Helps users to locate admin block

 Intent_Name: Science lab
 Purpose: Provides directions to science labs.

 Intent_Name: library
 Purpose: Shares library location, timings.

 Intent_Name: comp lab
 Purpose: Helps users to locate computer lab

 Intent_Name: Av room
 Purpose: Helps users to locate Av room

 Intent_Name: canteen
 Purpose: Provides canteen location.

 Intent_Name: kindergarten
 Purpose: Helps users to locate kindergarten block

 Intent_Name: primary block
 Purpose: Helps users to locate primary block

 Intent_Name: science block
 Purpose: Helps users to locate science block

 Intent_Name: swimming
 Purpose: Helps users to locate swimming pool

--> Detailed Entities and Their Functions

 Entity_Name: @mode
 Purpose: Identifies the type of transportation requested 
 
 Entity_Name: @admin_functions
 Purpose: Recognizes which office is being referred to (Admin or Reception).

 Entity_Name: @time_day
 Purpose: Detects the day type (Weekday, Weekend, Holiday) to provide accurate timings.

 Entity_Name: @class
 Purpose: Specifies the grade or class for which admission information is requested.

 Entity_Name: @building_name
 Purpose: Captures the building or block name (e.g., A Block, Science Block, Auditorium).

 Entity_Name: @department
 Purpose: Recognizes departments such as Library, Hostel, or Labs for navigation assistance.
