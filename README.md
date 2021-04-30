# DATA3406 ASSIGNMENT 2
Topic Two: PeerWise Groups :family:

Driving question :mag_right:
----------------
What are the impacts of the group membership for performance using PeerWise?

Table of contents :clipboard:
------------------
1. [Introduction](#introduction)
2. [The Team](#the-team)
3. [Getting Started](#getting-started-file_folder)
4. [Project Description](project-description.md)
5. [Raw Data](/data)
6. [Data Origin and Summary](#data-origin-and-summary-floppy_disk)
7. [Important Variables](#key-variables)
8. [Product Notebook](/Product_Notebook.ipynb)
9. [Process Notebooks](/process-notebooks)
   1. [Week 8 Process Notebooks](process-notebooks/Week%208%20Mini%20Assignments)
   2. [Week 9 Process Notebooks](process-notebooks/Week%209%20Mini%20Assignments%20Assignments)
   3. [Week 10 Process Notebooks](process-notebooks/Week%2010%20Mini%20Assignments)
   4. [Week 11 Process Notebooks](process-notebooks/Week%2011%20Mini%20Assignements)
   5. [Further Exploration Process Notebooks](process-notebooks/Further%20Exploration)
10. [Group Processes](Group_processes)
11. [Group Process Report](Group%20Processes%20Report.pdf)

Introduction
-------------
Establishing if working in organised teams can significantly influence performance on peerwise will be beneficial to both teachers and students. Results have shown that academic improvement is especially pronounced within relatively small cohorts and can even boost student performance. In addition to this student performance and engagement is of great interest and importance to educators like Gareth Denyer, a Professor here at the University of Sydney.

The Team:
---------
| Names   | Role    |
|---------|---------|
| Abdullah| Manager |
| Charlie | Tracker |
| Tash    | Member  |
| Yan     | Member  |
| Johanna | Member  |
| Taron   | Member  |


Getting Started :file_folder:
--------------
**Short list of intructions for new collaborators to get up and running with the project.**

List of commands:

- `$ git clone https://github.com/abdullahsafi/PeerWise_Group_Performance.git`
- `$ cd PeerWise_Group_Performance`
- Here you can access the Product Notebook and other folders.
- The Product Notebook can be opened through Google Colab (recommened):
   - Ensure you upload your copy of the repo onto your google drive
   - There is a path variable for you to link the data
- The Product Notebook can be opened through Jupyter Notebooks:
   - Ensure that modules and dependancies are downloaded

Data Origin and Summary :floppy_disk:
------------

**Origin of data**

Gareth Denyer has made extensive use of PeerWise in large classes at Sydney University. He has a set of de-identified data for students who worked in groups which he has classified in terms of their motivation and achievement levels. The data available is from internal PeerWise logs and final exams. Gareth has agreed to be available to discuss this topic with groups taking it on. Students who want to do this project need to be linked to the ethics processes for analysing this data.

**Summary of files, tables, and fields.**

| Data File | Description | 
|--------------|----------------|
|Comments data | Comment data including the author, the question it was posted on, the time it was posted, and the content of the comment |
| Edits data | Data about edits to questions including the id of the old question, id of the new question, and the time the edit was made |
| Ratings data | Data of ratings on questions including the question id, rater id, and the quality/difficulty score given |
| Tags data | Data of the tags on questions including the tag, question id, and tag id |
| Courses data | Data of each course including the course name, course id, and relevant start/due dates for the cycles |
| Questions data | Data about questions posted by students |
| Courses data | Data of each course including the course name, course id, and relevant start/due dates for the cycles |




Key Variables
---------
**Description of variables that are important throughout the Notebooks.**

| Key Variables | Description | 
|--------------|----------------|
| User           | Used to uniquely identify a user of the PeerWise platform (anonomous) |
| Team           | The team that a user is assigned to. Can be used to evaluate size of teams and investigate team performance |
| QuestionID     | Used to uniquely identify a student published question |
| Comment_ID     | Used to uniquely identify a student published comment  |
| Timestamp      | The time an event occured (such as posting a comment, position a question, answering a question) |
| avg_rating     | The average student-given rating of a student-published question          |
| AcademicMark   | A mark assigned by academic staff to a student's question based on its quality |
| Answer         | The correct answer of a question    |
