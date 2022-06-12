CoolCall: a computer system for cold-calling students
=====================================================


Authors: Arden Butterfield, Quinn Fetrow, Derek Martin, Amy Reichhold, Madison Werries


====


Created January 6 -- 30, 2022, for Project 1 of CIS 422, Winter 2022, with Anthony Hornof.


====


Last modified January 30, 2022


====


To run the program, run python3 CoolCall/app/cool_call.py in the terminal. Further instructions can be found in the Installation Instructions and User Documentation documents.


This program requires a version of python from 3.7 to 3.10, with the standard library.


====================================================


Files in this archive:


====


README.txt
This file here. Describes the overall layout of the project.


====


SRS.pdf
Describes the ConOps and requirements for the system.


====


SDS.pdf
Describes the design and architecture of the system, with static and dynamic models of each module.


====


Project_plan.pdf
Describes the plan for working together as a group, and an overview of our meetings.


====


Programmer_Documentation.pdf
Documents the structure of the system from a programmer’s perspective.


====


Installation_Instructions.pdf
Instructs the user in how to install the system.


====


User_Documentation.pdf
Instructs the user in how to use the system


====

sample_roster.txt
An example roster file, for use in testing the system.


====


CoolCall/
The directory of the application.


====
CoolCall/logs/
The directory where the software writes summary files and daily log files.


====


CoolCall/app/
The directory where the code resides.


====


CoolCall/app/cool_call.py
The main function of the system. This is the file to run with python to run the app.




====


CoolCall/app/constants.py
Constant values that can be modified to change how the system runs. Discussed at greater length in the User Documentation document, and in the comments of this file.


====


CoolCall/app/instructor_interaction_model.py, CoolCall/app/student.py, CoolCall/app/key_sequence.py, CoolCall/app/student_queue.py, CoolCall/app/log_manager.py, CoolCall/app/display.py, CoolCall/app/random_distribution_verification.py, CoolCall/app/student_roster.py
The other source code files of the app. Their functionality is described in the Programmer documentation, as well as in the comments of the files themselves.


====


CoolCall/app/student_test.py
A test file for the methods of the Student class.


====


CoolCall/app/student_data/
The internal directory where our application stores student data.