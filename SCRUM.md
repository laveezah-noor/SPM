# SCRUM
Scrum is a specific Agile framework that provides a structured approach to manage software development projects. 
- It divides the development process into fixed-length iterations called "sprints," typically lasting 1 to 4 weeks. 
- The Scrum team consists of roles like Product Owner, Scrum Master, and Development Team. 
- The Product Owner is responsible for prioritizing the backlog and ensuring the team delivers the highest business value. 
- The Scrum Master facilitates the Scrum process, removes impediments, and helps the team stay focused. 
- The Development Team is self-organizing and cross-functional, responsible for delivering potentially shippable increments each sprint. 
- Scrum events include Sprint Planning, Daily Stand-up, Sprint Review, and Sprint Retrospective, which promote collaboration and inspection. 
- The Scrum framework emphasizes transparency through artifacts like Product Backlog, Sprint Backlog, and Increment. 
- Scrum enables adaptability by allowing the team to adjust priorities and requirements based on feedback and changing business needs.

![[Pasted image 20230724125329.png]]

----------
## Project Kick-Off Meetings
- Team Members Introduction
- PM explains the Project Scope and Overview briefly
- Shares the tentative timeline or Deadline of Project
- Answers any Initial queries from Team


## Project Planning / Sprint Planning Meeting
- Team or Project manager breaks down the List of Requirements in Priority order => **Product Backlog**
- Team picks the Top Priority Requirements and time box them into First Sprint.
- Every member picks his task i.e. **User Stories** and provides estimates or story points.
- Any technical inquiries or question are made in this meeting regarding any requirement.
- A sprint planning meeting should be one of the longest Scrum meeting you hold
- Plan on two hours of planning each week of your sprint.
- 

## Daily Standup Meeting
- Daily stand up meeting only takes 15-30 mins. Its an effective way of keeping all the members Up-to-speed, on task and communicating each other.
- Scrum Team Roles
	- Scrum Master
	- Product Owner
	- Team
- Three questions to ask
	- What they did  yesterday??
	- What they will do today?
	- What problems they face in their task in progress?
- Any detail discussions are discussed separately after the meeting.
- 


## Scrum Review
- A sprint review is an event that occurs at the end of a sprint in Scrum methodology. The purpose of the sprint review is to inspect the outcome of the sprint and determine future adaptations. 
- During the event, the Scrum Team presents the results of their work to key stakeholders and progress toward the Product Goal is discussed. Based on this information, attendees collaborate on what to do next. 
- The Product Backlog may also be adjusted to meet new opportunities.
- The Sprint Review is timeboxed to a maximum of four hours for a one-month Sprint. For shorter Sprints, the event is usually shorter.

## Sprint Retrospective
- A sprint retrospective is an event that occurs at the end of a sprint in Scrum methodology. The purpose of the sprint retrospective is to plan ways to increase quality and effectiveness. The Scrum Team inspects how the last Sprint went with regards to individuals, interactions, processes, tools, and their Definition of Done.

## Development - Testing - Bug Fixing - Verification
- Dev Team does development of sprint on their Development server.
- While QA Team prepares their test cases for the sprint module.
- After unit testing, Dev Team releases build on QA Environment.
- QA Team performs testing on provided build against Test Cases and Requirements.
- QA Team reports the bugs or error found in build
- QA Team marks the status of Test Cases as Pass/ Fail.
- Dev Teams work on new sprint of items
	- based on sprint meetings, Team picks next high priority item from Product Backlog
	- this cycles continues, until all Clients requirement are fulfilled listed in Product Backlog
- Or Dev Teams works on bugs and provides new build with fixes
- QA Team performs Testing on new sprint with new modules
- Or QA Team verifies the fixes and update the bug reports and test cases.

## User Acceptance Testing
- Product Owner or any representative of business team for client performs the User Acceptance Testing.
- QA Team runs these UAT Testcases or business scenarios first.
- If the Client passes the UAT, the build is pushed to production or live.
- If the UAT is failed, the Dev Team works on the bugs and after QA Team passes it, UAT is performed again to approve or accept the build.

## Change Management
- During any sprint, Client can send some change request for ongoing work.
- Product Manager puts it in Product Backlog and based on priority includes in the next sprint.
- Due to Weekly or Monthly sprint releases to Client, Team keep getting feedbacks from Client and they can update or fix any change or defect the client report.

## Production Release & User Training
- After all the UAT is passed and Client signs off, the final build is deployed on Production GO Live.
- Project Team helps in training the end users or Business users