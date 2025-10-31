# IDAI101-1000405-Rakshmi-Priyasree-M
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

-> Detailed Intents and Their Functions
      ->Transportation Bot
                  Intent_name:	Provides details about transport modes available (bus, van, etc.), timings, and routes for students and staff.
🏢 Office Timing Bot
Intent Name	Function
Office_Hours_Admin	Gives working hours of the Administrative Office on weekdays/weekends.
Office_Hours_Reception	Shares the Reception office’s timing and contact info.
Holiday_Information	Provides information about campus holiday schedules.
🎓 Admission Bot
Intent Name	Function
Admission_Process	Explains how to apply for admission.
Admission_Eligibility	Provides eligibility criteria for different classes.
Fee_Structure	Shares details about fee payment and deadlines.
Document_Requirements	Lists documents required for admission.
Scholarship_Info	Gives details about available scholarships and how to apply.
🧭 Campus Navigation Bot
Intent Name	Function
Find_Building_Location	Helps locate a specific building/block on campus.
Find_Lab	Shares directions to labs or computer centers.
Find_Library	Guides users to the library location and timings.
Find_Hostel	Provides location and facilities of the hostel.
Find_Department	Helps identify departmental blocks and their rooms.
Find_Canteen	Shares canteen directions and timings.
Find_Playground	Shows route to the playground or sports area.
Find_Parking	Guides users to parking zones.
Event_Venue_Location	Provides event or seminar venue details.
Campus_Map	Displays the overall layout and building map link (if integrated).
🔤 Detailed Entities and Their Roles
Entity Name	Function
@mode	Identifies the user’s preferred transportation method (e.g., bus, van, cab).
@office	Recognizes which office the user refers to (Admin or Reception).
@day_type	Detects the day type to provide correct timings (Weekday, Weekend, Holiday).
@class	Used to filter admission info based on grade/class (e.g., Grade 6, Grade 11).
@building_name	Captures names of buildings or blocks on campus (e.g., A Block, Science Block).
@department	Recognizes departments like Library, Hostel, or Labs to provide directions.
