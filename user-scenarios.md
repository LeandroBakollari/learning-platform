#  User Scenarios for School Management System

| ID  | Role      | Title                        | Description |
|-----|-----------|------------------------------|-------------|
| 1   | Parent    | Parent Logs In               | A parent opens the login page, enters credentials, and gains access to their dashboard. If credentials are incorrect, an error is displayed and the login fails. |
| 2   | Parent    | Switch to Pupil View         | After logging in, a parent chooses to switch to their child’s (pupil's) view, gaining access to limited features such as viewing assignments and grades. |
| 3   | Parent    | View Pupil’s Grades          | Parent views grade records for their child, sorted by subject and teacher, with an option to download a grade report. |
| 4   | Parent    | View Attendance              | Parent checks the pupil’s attendance history, including details on absences and late arrivals. |
| 5   | Parent    | Message Teacher              | Parent composes a message to a specific teacher about academic concerns. The teacher is notified and can reply. |
| 6   | Parent    | Read Teacher Reply           | Parent opens and reads the teacher's reply. The message is marked as read with a timestamp. |
| 7   | Parent    | Receive Notifications        | Parent receives alerts for absences, new grades, assignment submissions, or teacher messages. |
| 8   | Teacher   | Teacher Logs In              | Teacher logs in using school credentials. Their dashboard loads with class and material management tools. |
| 9   | Teacher   | Create a Class               | Teacher opens a form to create a new class, enters the details (subject, grade, etc.), and submits it for approval. |
| 10  | Teacher   | Add Pupils to Class          | Teacher assigns pupils to an approved class either by selecting from a list or adding them manually. |
| 11  | Teacher   | Upload Material              | Teacher uploads materials (PDFs, videos, etc.) for a class. Pupils and parents are notified. |
| 12  | Teacher   | Create Quiz or Assignment    | Teacher creates a quiz or assignment, adds instructions, a deadline, and optionally uploads files. |
| 13  | Teacher   | Grade Submissions            | Teacher reviews pupil submissions, gives grades, and provides feedback. Parents are notified of results. |
| 14  | Teacher   | Mark Attendance              | Teacher marks daily attendance for each pupil in a class. Absences trigger notifications to parents. |
| 15  | Teacher   | Message Parent               | Teacher sends messages to one or more parents, viewable in their inbox. Replies are tracked. |
| 16  | Teacher   | View Class Overview          | Teacher views analytics about class performance, grade distribution, and attendance patterns. |
| 17  | Principal | Principal Logs In            | Principal logs into the system and accesses school-wide management tools and reports. |
| 18  | Principal | Approve Class Request        | Principal reviews and either approves or denies class creation requests submitted by teachers. |
| 19  | Principal | Manage Accounts              | Principal edits, deactivates, or deletes user accounts (teachers, parents, pupils) and can reset passwords. |
| 20  | Principal | View Teacher Performance     | Principal views a performance dashboard for teachers, including pupil grades, feedback, and attendance. |
| 21  | Principal | Send Announcement            | Principal sends announcements to all users or specific roles. Messages appear pinned in the dashboard. |
| 22  | Pupil     | View Assignments             | Pupil (accessing through parent account) views a list of upcoming and past assignments with deadlines. |
| 23  | Pupil     | Download Materials           | Pupil downloads study materials shared by the teacher for review and preparation. |
| 24  | Pupil     | Take Quiz                    | Pupil selects and completes a quiz online before the submission deadline. Results are stored. |
| 25  | Pupil     | Submit Assignment            | Pupil uploads their completed assignment for the teacher to review and grade. |
| 26  | Pupil     | View Grades                  | Pupil views their grades and teacher feedback for past assignments and quizzes. |
| 27  | Pupil     | View Messages                | Pupil reads messages sent by the teacher if messaging is enabled for them. |
