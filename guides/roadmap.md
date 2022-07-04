# Roadmap

## SRS

* [ ] Actors
  * [ ] Program Coordinator
  * [ ] **Lecturer**
  * [ ] **Student**
  * [ ] **Employee**
  * [ ] **Management**
* [ ] Use cases
  * [ ] Program Coordinator
    * [ ] Login
    * [ ] accept student registration list (select multi-students) and approve or reject
      * [ ] Create record in students table for each approved student from registration
      * [ ] **Insert record for each student in table students-takes**
      * [ ] Create username/password for student in table users
      * [ ] Send username/password to student email
    * [ ] **Maintain users accounts (for lecturer, employees, managers)**
    * [ ] **Maintain programs information (diploma/master/PhD)**
    * [ ] Maintain Courses information (inside programs)
    * [ ] **Maintain lecturers’ information (personal/educational)**
    * [ ] **Assign courses to lecturers**
    * [ ] **Maintain teaching time slots for program**
    * [ ] Trigger the system to generate program time table (based on lecturer preferences for time slots, avoiding that same program/lecturer has two sessions in the same time slot)
    * [ ] Trigger the system to create “teams” in Microsoft Team for each program and add admitted students and lecturers as a members (release 2)
    * [ ] Trigger the system to create online sessions (auto recording) for program timetable in Microsoft teams
    * [ ] **View courses recordings for a program**
    * [ ] **Send Announcements to lecturers’ group**
    * [ ] **Send Announcements to students’ group**
    * [ ] **admit students to complementary courses (from other programs) (release 2)**
      * [ ] select program, select course from program
      * [ ] select a program, search for students flagged with complementary courses
      * [ ] assign multi-students to the course
      * [ ] add to table students-takes (student id, course id, year, semester, type{Comp})
    * [ ] Evaluate courses (questionnaire) (Relese2)
    * [ ] **Evaluate lecturers (questionnaire) (Relese2)**
    * [ ] **Reports and KPIs (Relese2)**
      * [ ] **courses**
        * [ ] attendance % for each course
        * [ ] teaching time % for each course
      * [ ] **lecturers**
        * [ ] teaching time % for each lecturer
        * [ ] courses success % for each lecturer
      * [ ] **students**
        * [ ] attendance % for each student
        * [ ] courses grades % for each student
      * [ ] **Respond to inquiries (Relese2)**
  * [ ] **Lecturer**
    * [ ] Select teaching time slot preferences (five preferences)
    * [ ] View his time table (from different programs)
    * [ ] **Start/end online session**
    * [ ] **Maintain students’ grades for a course**
      * [ ] Update Students-takes (attendance, assignment, quiz, exam1, exam2, grade)
    * [ ] **View his courses recordings**
    * [ ] **Manage course material**
    * [ ] **Manage assignments for students**
      * [ ] Year, semester, Course, Assignment name, description, due date, grade, attachment
    * [ ] **Send Announcements to students -R2**
    * [ ] **View students’ attendance**
    * [ ] **manage online Quiz**&#x20;
    * [ ] **manage online exam**&#x20;
    * [ ] **Respond to inquiries (Relese2)**
    * [ ] **Manage blog (Relese3)**
  * [ ] **Student**
    * [ ] **Request program registration**
    * [ ] **View his timetable**
    * [ ] **Attend session**
    * [ ] **Send inquiry for lecturer - R2**
    * [ ] **Send inquiry for coordinator - R2**
    * [ ] **View/download course material**
    * [ ] **View/download course recordings**
    * [ ] **Respond to assignment (Upload assignment solution)**&#x20;
    * [ ] **View courses grades**
    * [ ] **Attend Exam/Quiz (Release2)**
    * [ ] **Pay online using Fawry gateway (release3)**
    * [ ] **Get university email account (release3)**
    * [ ] **Manage blog (Release3)**
  * [ ] **Employee**
    * [ ] Register students in program (same as student interface)
    * [ ] **Maintain students’ information**
    * [ ] Maintain teaching locations information (halls/labs)
    * [ ] **Send Announcements to students**
    * [ ] **View Students payment status report**
    * [ ] **View students’ registration condition report**
  * [ ] **Management**
    * [ ] **Program report (semester, program, #students, success %, teaching time, #lecturers)**
    * [ ] **Teaching report (semester, lecturer, #courses, teaching %)**
* [ ] System Objects
  * [ ] **User**
  * [ ] **Program**
  * [ ] **Course**
  * [ ] Time Slot
  * [ ] Semester
  * [ ] **Timetable**
  * [ ] Student
  * [ ] **Lecturer**
  * [ ] **Assignment**
  * [ ] **Announcement**
  * [ ] **Exams (release2)**
  * [ ] **Quiz (release2)**
  * [ ] **Blogs (release3)**
* [ ] Quality requirements
  * [ ] **Usability**
  * [ ] **Performance**
  * [ ] **Scalability**

## StudentPlus App 1.0

### Frontend

* [ ] Student
  * [x] Register
  * [x] Login
  * [x] Forgot password
  * [ ] Account
    * [x] Student profile
    * [x] Security
    * [ ] Notifications
  * [x] Uni Connect
    * [x] Programs
      * [x] Program details
    * [x] Study Programs
    * [x] Wishlist
    * [x] My applications
  * [ ] Plus membership
    * [ ] My Schedule
    * [ ] Materials
    * [ ] Lectures
    * [ ] Your results
    * [ ] Your requests
* [ ] Teacher
  * [x] Register
  * [x] Login
  * [x] Forgot password
  * [ ] ...
* [ ] Site Infra
  * [x] 404
  * [ ] landing page
  * [ ] Status

## StudentPlus App 2.0
