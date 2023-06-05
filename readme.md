🛠️ Talent Recruiter Application 🛠️
Talent Recruiter Application is a project management application built in Daml.

I. Overview
This project was created by using the empty-skeleton template. The project adopts and exemplifies the proposal-accept design pattern.

A student can propose himself as a talenter to his academy recruiter, in order to get listed in the list of the academy's talents. The recruiter is not the final person to decide about this. The recruiter will need to get the approval of the academy's inspector. 
Once recruiter and the inspector approving the proposal, that's when the student will be added to the list of talents.

II. Workflow
The student proposes himself as a talent and sends it to the academy' recruiter. 
The recruiter revise the application and accepts his proposal, and creates a new proposal for the academy's inspector. 
The inspector review the application and asks for more details about the request.
The recruiter replies with the required information, indicating that the student can hold his breath under the water for 4 mintes. 
The inspector reviews the information and decided to accept the application, and adds the student to the list of talents.  

III. Compiling & Testing
please run the following command to start the application initial setup
$ daml start