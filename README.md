# database-output
SQL database design for a school database consisting of the teacher, student, class, department and level tables with relationships.

The teacher table would contain teacher data, likewise the student table would contain student data. The class and department tables would contain all the classes and departments in the school respectively, and the level table would contain the various teacher levels and their salaries.

Appropriate relaionships are shown.

Queries that can be run:
1. INSERT INTO studentTable VALUES (724, "Mary-Theresa", "Nwankwo", "F", 2002, JSS3, 03-09-1991, 1):
This would add the new data to the studentTable

2. SELECT id, first_name FROM teacherTable WHERE id = 1:
This would read the value of first_name in the teacherTable where the id is 1

3. UPDATE classTable SET class_name = 'SS3' WHERE id = 6:
Ths would update the existing data, supposing it was already there before

4. DELETE FROM departmentsTable WHERE id = 1:
This would remove the existing row from the departmentsTable, whaere id is 1

5. SELECT id, name FROM salariesTable:
This would select all the id's and name fields on the salariesTable
