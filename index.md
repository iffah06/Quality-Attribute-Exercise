Exercise Chapter 2
1.	Identify 3 QAs for each system

Enterprise inventory control = 	Availability, Security, Interoperability
Smart phone map app = Availability, Security, Performance	              			              			
Video game = Availability, Performance, Modifiability
Social network site =  Availability, Security, Usability                                                       					


2.	Specify the most important QA for each system using scenario

Enterprise inventory control (Security)
Scenario: Hacker tries to log in
Source: Unknown
Stimulus: Hacker tries to log in using staff id and password
Environment: Runtime
Artifact: System
Response: Account request for 2 factor authentication
Response Measure: Account is freezed after 4 trials

Smart phone app (Performance)
Scenario: Users wants to open the application
Source: Users
Stimulus: User tries to open application 
Environment: Runtime
Artifact: Application
Response: Application must be smooth and efficient
Response Measure: Opening the application must take under than 2 seconds

Video game(Performance)
Scenario: User tries to use multiple keys on keyboard
Source: User
Stimulus: User want to use skills on video game
Environment: Runtime
Artifact: System
Response: Games run smoothly
Response Measure: The time it takes for system to respond to the user action must take under less than 2 seconds

Social network site (Availability)
Scenario: User wants to use the social network site 
Source: User
Stimulus: User tries to use the social network site at 3 am 
Environment: Runtime
Artifact:System 
Response: Social network site must be available 24/7
Response Measure: Opening the application must take less than 3 seconds and the flow of the site must be smooth
