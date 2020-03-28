# Iteration Plan

## Objectives

 - The purpose of this application is to allow a new useful update on the school website
 
 - The purpose is to allow ordinary users, such as parents and students of ITIS G. Marconi, to more easily find the most appropriate companies for the student who must complete the experience of alternating school work
 - After logging in, the student can, through a filter table, perform a search according to their school address and according to their country of residence, to find a company convenient to their needs
 - The table will allow the selection of the company in question which will open a page where the information of that specific company will be displayed. Then you can have an address and the number of the company to be able to contact it and ask information about it
 
## Use Cases

 -   There will be two types of users who can access this application with two different interfaces. The first will be the common users who can choose the company and then notify the school tutor of the choice made, the second user is precisely the school tutor, together with certain professors
 
 -   The tutor interface is an editable interface, in fact the tutor will be able to add companies with all similar fields and even delete them if they are no longer affiliated with the school
 - It will also be able to modify the existing fields of a company, for example if that company has changed its address or ateco code
 - To choose a company, common users will be able to rely on a project made by students in the past in that company, so as to understand in which field and area they will go to carry out their work

## Task Schedule
| Task | Effort | Completiton Date | Status
|--|--|--|--|
| Create ETL process | 8/9 | 15/02 | Finished |
| Create a form html | 5 | 20/02 | Finished |
| Create a request php with difference of common users and tutor | 7 | 1/03 | Finished |
| Found a filter table for common users and edit it | 8 | 10/04 | Started |
| Found an editable table for tutor | 9 | 10/04 | Not Started |
| Create a linkable field for information of companies | 9 | 10/04 | Not Started |


 -   As a first point, you need to create a form with html that allows the input field
 
 -   Next you need to send the information given in the form on a php page that processes it with the Classeviva algorithm and see if the user is a student or a teacher or tutor
- Once the records have been processed, the user will be directed to his page depending on what type of user he is and here he can start interacting with the page


