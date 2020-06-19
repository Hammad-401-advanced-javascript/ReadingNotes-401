# 401 Project

![image](https://ibb.co/ZcgThnb)

## the home page

1- There are three users for our site : developer, student,instroctor.

2- I will sign up with my role and the data will stored in the db, also, i can sign up by google +facebook+yahoo.(aouth,basic)

3- when i sign in i will aouth my account to see what the capapilities that i have, and that by my token(bearer,acl).

## profile :

4- here the student can edit his information , also the instrctor can do that and he can add the courses that he will teach.

5- in the user module i can do CRUD to do this step, by the instance from the schema in the db.

## main :

6- as a student/instrctor i can add the course that i want in my dashboared.

7- here we will do two steps:

**firstly: we should get all the courses to this page.**

**secoundly: added the courses that the student/instructor select (from courses schema) to the (users schema).**

## dashboard:

8- as a student i can see the courses that i select in my dashboard and i have access to every course to see : (bio about the course,
bio about the instructor,celander,silipas,assignment,my grade,certificate, link for the course room in Q&A page,Withdrawal from the 
course), when i press open course.

9- as a instrctor i have a page that contain tha courses that i will take(as a student above), and i have in the same page the
courses that i will teach, and when i press on the one off my coures i can see : (my student,calender, grade system, exam system,
Attendance and absence schedule, link for the course room in Q&A page).

10- 

**-student: we will use read to get all the courses that the student select from (user schema)**

**-student: we will use(read and post) to interactive with the properites that we add in the course page, which 
 is : (bio about the course,bio about the instructor,celander,silipas,assignment,my grade,certificate, link for the course
 room in Q&A page,Withdrawal from the course)**
 
11- in addition for the proparities above (if the instctor wanna take a course like a student), we can use all the CRUD methods to make the instrctor deal with his responsibilities (my student,calender, grade system, exam system,Attendance and absence schedule, link for the course room in Q&A page).

## Q&A:

12-
**as a student i can chat with my colleguies in the same course and with the instrctor.**

**as a instrctor i can chat with my student and answer there questions.**

13- here we can will have a real time chat ,contain rooms for every course , and any course will have his room.

14- as a strch goal: we can use massege queue to make our chat more real rather than chatting whithout saving the massege
, and we can do that if we saved in in chat schema.
