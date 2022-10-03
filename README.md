# ONT-2000-year-project
This project is due on the 28 October 2022.   All students should work in groups of 5, unless you have one extra person, in which case you will need to let me know.   All programs should be developed using the 3-tier application.   All programs should make use of Validation, and RegularExpressions where necessary.   Only one student should submit both the documentation and the project.   A non-functional project will result in all students getting a zero for the project.   For the illustration video, you are required to add the link to the recording in your documentation.

Project Instructions 
• You are required to work in groups of no more than 5 students. 
• Students are required to submit a working program, along with database files, and a 
documentation for the project. 
• A working database will be shared with students, which will assist in them creating their own 
database. 
• Students are required to record their projects and attach a link to the video where the project 
is illustrated. 
• Plagiarism (Copying another students’ work will result in all groups that are found to have 
plagiarised to get a zero and sent for disciplinary). 
All Projects need to:
• Be developed using the 3-tier architecture. 
• Be fully tested for any errors. 
• Input validation to filter informal and unwanted input should be used. 
• Make use of version control, such as Team Foundation Server, or Azure, or GitHub. 
• NB: No primary key, or foreign keys should be hardcoded into input fields (i.e., using textboxes 
for foreign keys). 
• Submit Deliverables as set on the Moodle site. 
• No late submissions will be accepted. 
• No submissions without videos recordings links will be accepted. 
You have recently learnt about 3-tier architecture programming and how to develop software using 
this technique. With this knowledge, you have been tasked to develop a software application for 
managing property rentals for various property agencies. The application should allow properties to 
be posted which can be available to people wanting to rent the properties. Properties should also 
include their locations. Properties are also managed by property agencies which have agents which 
are responsible for specific properties. When a tenant requests to rent a property, the rental should 
be recorded, including information for the property they are wanting to rent, and the agent 
responsible for the property, as well as the start and end dates for the rental. Below are the various 
responsibilities for the various users of the system:
Administrator
• Responsible for managing properties, property types, locations, agencies, and agents. 
Agent
• Responsible for managing properties and rentals. 
Tenant
• Responsible for applying to rent a property. 
The minimum requirements for the system are:
The requirements listed below relate to the tables in the database. 
1) Manage Property Type (Add, and Display)
2) Manage Properties (Add, Update (TypeID, Price, Status), Display, Delete)
3) Manage Province (Add, and Display) 
4) Manage Cities (Add, and Display)
5) Manage Suburbs (Add and Display)
6) Manage Agencies (Add, Display, Delete)
7) Manage Agent (Add, Update (Email, Phone, Status), Display, and Delete)
8) Manage Tenant (Add, Update (Email, Phone, Status), Display, and Delete)
9) Manage Property Agent (Add, Update (PropertyID, AgentID, Date), Display)
10) Manage Rental (Add, Update (StartDate, EndDate), Display)
You are allowed to add more functionality to the system which you deem necessary, however, that 
can only be done once the minimum requirements for the system have been met. 
From the minimum requirements of the system, there will be information that will be collected from 
the users of the system, which will be used for generating reports in the system. Reports will count 
more marks than the requirements of the system, therefore, students are required to pay more 
attention when working with these reports. 
Below is a list of minimum reports that all student systems should include:
• List All records for users (agents, admin, and tenants)
• Display information of a selected user type (agent, admin or tenant)
• Display properties, and property types. 
• Display cities, provinces, and suburbs. 
• Display rentals for tenants and the agents responsible. 
• Display rentals which have ended. 
• Display rentals based on specific amounts. 
• Display tenants and properties they have rented over time. 
• Display agencies which manage the most properties.
