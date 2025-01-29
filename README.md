# OOP-assignment-2
Using classes and arrays, the students will develop a set of functions for the Hospital
System. The system is represented by following structure
● Write the code of the class Doctor as follows:
1. Create class "Doctor".
2. Declare all the instance variables as protected for the Doctor class: id, name,
duration (which represent total number of minutes Dr spent with patients), and
rate.
3. Create a default constructor for the "Doctor" class

4. Create a parameterized constructor for the "Doctor" class.
5. Create a function named calculateTotalFee().
7. Define “PrettyPrint” function that returns the id and name of the doctor in a
formatted string as follows.
Doctor ID is D057, and name is Dr. Muhammad Mahgoub
● Write class surgerySchedule as follows
a. Create class SurgerySchedules.
b. Declare instance variables as private for the class patientName :string ,
Date:string.
c. Create a default constructor for the class
d. Create a parameterized constructor for the class.
e. Create setter & getters.
● Write the code for class “Surgeon” as follows:
a. Create the "Surgeon" class as a subclass of the "Doctor" class.
b. Declare private instance variable numSurgeriesScheduled :int and dynamic
array of SurgerySchedules objects.
c. Create a default constructor for the class.
d. Create a parameterized constructor for the class.
e. Create a copy constructor for the class.
f. Create a destructor to delete allocated memory.
g. Override calculateTotalFee() method, which returns the total fee as:
The product of number of hours Dr spent with patients * rate
= (Duration/60 ) * rate.
h. Override the PrettyPrint method to return the doctor's name and total fee and
numSurgeriesScheduled in a formatted string as follows
“Dr. Muhammad Mahgoub is a surgeon whose total fee is 525.0.”
i. Add a member function printSurgeries, which prints all of the scheduled
surgeries of the surgeon.

● Write the code for class “Specialist” as follows:
a. Create the "Specialist" class as a subclass of the "Doctor" class.
b. Declare private instance variable of the "Specialist" class: speciality(string)
c. Create a default constructor for the class.
d. Create a parameterized constructor for the class.
e. Override calculateTotalFee() method, which returns the total fee as a product of
the number of quarter hour Dr spent with patients * rate = (duration / 15) *
rate.
f. Override the PrettyPrint method to return the doctor's name and total fee in a
formatted string as follows
“ Dr. Muhammad Mahgoub is a Specialist with whose total fee is 525.0”

In Main.cpp
// Ask user to enter number of Doctors in system
// loop for number of entered Drs
// ask user if the Dr is specialist or surgeon
// take Dr details based on user choice
//End Loop

//open a file called doctors.txt
// loop for number of entered Drs
// call PrettyPrint in each iteration to print all Drs fees. Print the returned string to
// both of the output screen and the output file
// call printSurgeries for surgeons only
//End Loop

Writing Good Quality Code
No program stays the same. It will need to change to fix bugs, add new features, etc.
So, It is very important to write high quality readable code, so that you or other
developers can be able to review and modify this code in the future. In this task, you
will:
1. Add a header to your program saying who the author is, the purpose of the program,
etc.
2. Add a header for every function explaining what it does, what parameters it takes and
what value it returns.
3. Write the code following C++ coding style.
http://geosoft.no/development/cppstyle.html 4.
4. Add comments to any part that is difficult to understand
