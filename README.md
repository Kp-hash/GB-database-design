# GB-database-design
Appendix A 
GB Training Organisation GBT is a training organisation that provides various training courses. The company has decided to put all the information they now keep manually into a database and to include course booking, accommodation booking, trainer allocation and room allocation in this new database. 
Background 
Students can apply for any of the courses provided. Each course has one or more trainers who are skilled in providing that course. A trainer is allocated to each course occurrence (actual course). If students attending a course require accommodation for the duration of the course, then accommodation is provided in local boarding houses which are booked by GBT and added to the overall cost of the course. They also keep a record of which students are booked into which boarding house and on which dates. 

Current System 
There is no standard method of receiving course applications. They can be made by telephone, letter or through a Course Application form which is issued with the Course Catalogue. If a student makes a general enquiry about a course, then the Student file is checked to see if he/she is a current student. If a student is not in the Student file then he/she is sent a Student Details form to complete together with the Course Application form. When the students return their Student Details form they are allocated unique student numbers and the students’ details are then added to the Student file.


Course Booking 
Upon receipt of a valid course application the Current Course file is checked for a vacant place on a currently organised course (actual course). If there is a place available, then the student is allocated to that course (actual course) and notification details are sent to the student. 

If there is not a place currently available on a Current Course, students are allocated to the Type of Course they wish to attend. When there are enough students waiting to attend a course then a new actual course is set up and students waiting for that course are sent notification details and allocated to a Current Course (actual course). 

When a student is notified of his/her acceptance onto a course, possible accommodation details are sent out and an accommodation booking is subsequently made, if required. 

A training room is allocated to an actual course by the Course Booking Section. Only one room will be allocated for each course run. The training room list is checked for available rooms, an available room is allocated and the room list is updated. Trainers are then allocated to the actual course. The system must check which trainers are qualified to teach that particular course and which trainer is currently available to be allocated to the course.
