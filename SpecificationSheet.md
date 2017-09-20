# General Specification Sheet

_Summary:_ We are making a webportal which will handle basic needs of Students, Instructors, and the Trip’s Liason.  
Each will have their own Role-based permissions (what they can see and do on the website) which will vary slightly.  
* The `Liason` will be able to generate reports (ex. t-shirt size list/number per size), 
* `Instructor` will be able to post course material & and edit the calendar, etc, and 
* `Student` should be able to see their grades and post their weekend plans.  
* `All Roles` will be able to view full list of contact info, student weekend trip plans, access discussion board, etc.  For each of these 3 roles, we need Use Cases, User Stories, and possibly a spec document that just outlines the role as a whole.  We also need to develop a single db schema to store information for all of these roles in a central place.  And we need to figure out (and possibly mock up) the UI/UX for the website as a whole and each role.    

> Students includes all students in the Bremen program (UNCW & from other Universities)

> [Note: the role descriptions above are just very brief of each role, not comprehensive.  See below for more information]

## RBAC Roles

### All Roles / Person Class
#### Access Details
* Emergency Contact List
* Complete, searcheable contact list of students, instructors, advisors & liason(s)
* Student Weekend Plans
* Fill out Questionaires
* View calendar with deadlines
* Edit details about user profile, including a profile pictures

### Instructor
#### Access Details
* Thing
* Thing2
* Generate Grade Report

### Student
#### Access Details
* Be able to submit & edit their weekend plans
* Access FAQ for students
* Access a "to do before leaving" list
* Access currency conversion calculator
* Access translation system (perhaps via Google translate API)
* View grade from course
* Apply for program
* Check on application status

### Liason
#### Access Details
* Generate, View & Print Reports
  * Contact List
  * Weekend Plans of all involved
  * T-shirt Size
* System admin permission scheme
  * Add Users
  * Edit Users
* Thing3
