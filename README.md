# CS612RestfulServersAssignment
Create a RESTful web service that runs in a docker container

Project Name: Students Service

Data Model Intro:
- A students has an id, name and a list of courses he/she is currently registered for.
- A course has an id , name and score.
- A student can take multiple courses
- We have three methods in StudentService.java
    RetrieveAllStudents()	mapping– “/students”
    RetrieveCourse(String studentId)	mapping– “/students/{studentId}/courses”
    RetrieveCourse(String studentId, String courseId)		mapping– “/students/{studentId}/courses/{courseId}”
