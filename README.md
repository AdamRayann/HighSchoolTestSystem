# HighSchoolTestSystem
An Application for creating and executing high school exams in Java and MySql. The high school administration is interested in developing a computerized information system with the purpose of coordinating all examination activities within the school and enhancing the efficiency and reliability of exam management.


## Classes
1.**Teacher** - a teacher can create questions and exams that are saved in the database

2.**Student** - a student can execute both manual and computrized exams, also a student can get statistical data about his grades.

3.**Principal** - a principal can get reports and statistical data about the school.

## Structure
Pay attention to the three modules:
1. **client** - a simple client built using JavaFX and OCSF. We use EventBus (which implements the mediator pattern) in order to pass events between classes
2. **server** - a simple server built using OCSF.
3. **entities** - a shared module where all the entities of the project live.

## Running
1. Run Maven install **in the parent project**.
2. Run the server using the exec:java goal in the server module.
3. Run the client using the javafx:run goal in the client module.
4. Press the button and see what happens!

Sign-In Page:


![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/2c9e7c2c-6a91-4c23-b26e-3f0dfca14c3d)



Teacher's Home Page:
Here, the teacher can create, prepare, edit, and execute manual/computerized exams. Additionally, they can monitor ongoing exams and the number of participating students.



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/a1d72d5a-6114-41b9-aa20-ae83b3be69d9)



*Creating Questions:



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/8d7479ae-118f-4299-abae-29ccb30696bb)



*Building an Exam:



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/60dc557a-80d5-4f0c-9d0c-b241278efbca)



After constructing the exam, the teacher selects the execution method, sets the date, and assigns an exam code.



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/faf6a020-0df2-4d5a-a9ed-783088a74931)



Student's Home Page:



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/b3ecbe30-e431-4900-b32e-862b8e8d0108)



During an exam (for manual exams, the exam is downloaded as a DOCX file, which opens and closes automatically after the time limit):



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/6f9b8cc9-0ee1-46ae-9395-00e0fdcbece2)



Principal's Home Page:
The principal can grant extra time for ongoing exams, review questions, exams, grades, and statistical data across different courses. Additionally, new users can be added.



![image](https://github.com/AdamRayann/HighSchoolTestSystem/assets/129179113/992c5dba-d8a8-4298-87a4-b0479d3b542b)














