# Overview
In this project, I focused on testing as a critical part of any solution development, highlighting how different testing perspectives—such as internal development team testing and business user acceptance testing (UAT)—play key roles. UAT is often performed manually and serves as a vital "go/no-go" decision point, where the solution is tested to ensure that the input entered into the system produces the expected output. If the solution fails this test, it requires amendment and retesting before it can move forward into production.

Robotic Process Automation (RPA) comes into play by automating manual, repetitive tasks, particularly in front-end or UI automation. RPA helps save time and reduces human error, allowing testers and users to focus on more complex tasks.

For example, in the web application I worked on in Project 3, UAT would involve a team of testers manually entering input data into each web application field and validating whether the correct output is generated—in this case, checking if a new record is correctly displayed. This process, being repetitive and time-consuming, can be automated using RPA to streamline the testing and validation process, ultimately improving efficiency and accuracy before the solution is deployed to production.  

# How the automation works
Here is a video [AUTOMATION VIDEO](https://drive.google.com/file/d/1vojaLXjvr4_wOLyFD7V3sNigLwXRvL-R/view?usp=sharing). For the purpose of this video, to make it short I tested the automation with 5 records in the clients and projects. The automation goes through all the CRUD (Create, Read, Update, Delete) processes for each client and project.
In the end of the video I view the excel file to show the test results. The video also does not include the creating an account process, it starts from logging in but this automation contains are process to create an account. You can review it in this repository.

# Data Access 
The automation is tested on the [NWU Tech Trends](https://techtrendstelemetryportal.azurewebsites.net/) website. The records created are found from the excel file which is uploaded in this repository [NWU Tech Trends Data](https://github.com/BonnieSibisi08/CMPG-323-Project-4---42563690/blob/main/NWU%20Tech%20Trends%20Data.xlsx).
The excel contains over 40 records for clients and projects, this automation works perfectly on all of them.

# Robotic Process Automation
I created a basic UiPath process designed to perform user acceptance testing. The starting point for the automation is my MainFlow file, which organizes all my workflows and executes them sequentially.

![Screenshot 2024-09-09 104851](https://github.com/user-attachments/assets/47ea4a14-4c03-4ea3-9572-1b952edbb695)  
![Screenshot 2024-09-09 104918](https://github.com/user-attachments/assets/22d3e4a0-777f-475e-83ea-4b68ae404233)  

# Hosting
I successfully hosted the process in UiPath Orchestrator.
![Screenshot 2024-09-09 102249](https://github.com/user-attachments/assets/a6f330dd-1809-4f81-bc35-d561c5bd6811)   

![Screenshot 2024-09-09 032848](https://github.com/user-attachments/assets/900c736b-4de5-4cd0-a8f3-a8d50915a8f9)   

![Screenshot 2024-09-09 105633](https://github.com/user-attachments/assets/56cf8efc-6cce-42a4-96a8-219ff61dfff6)  

# Scrum Implementation
A [Stretch Task](https://github.com/BonnieSibisi08/CMPG-323-Project-4---42563690/issues/16) was added for this project, you can view it in the [Kanban Board](https://github.com/users/BonnieSibisi08/projects/2). I also linked this repository to the existing Kanban Project.
![Screenshot 2024-09-09 110007](https://github.com/user-attachments/assets/69aab06d-6c3a-4b25-99fd-59efbbe0765c)  

# References 
Here is a document that contains all the references which hepled in completion with the project: [Project-4: References](https://docs.google.com/document/d/17swgkpgLRmqayorEWh6ITouow4puxnnF/edit?usp=sharing&ouid=104985369547771360207&rtpof=true&sd=true)  






