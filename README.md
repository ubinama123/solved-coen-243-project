Download Link: https://assignmentchef.com/product/solved-coen-243-project
<br>






<strong>Purpose: </strong>The purpose of this project is to allow you practice Object Oriented Design, Pointers, File I/O, Exception Handling, Functions and Arrays.




<strong>Problem Objective: </strong>The objective of this problem is to create a fully functioning system that handles the records of students at Concordia University. Based on the following narrative, you need to come up with an Object-Oriented design to represent the different entities in the system.




<strong>Part 1: Student class </strong>

The initial information of <em>student </em>members is maintained in a file called <strong><em>student.txt (first line shows the number of lines)</em></strong>. Each record in this file is composed of:




<ul>

 <li>Student first name</li>

 <li>Student last name</li>

 <li>Student id</li>

 <li>Date of birth</li>

 <li>GPA to the date (Range: 0 – 4.4)</li>

 <li>Start year</li>

 <li>Completed credit</li>

 <li>Program (B: bachelor, M: master’s, P: Ph.D.)</li>

</ul>




You need to create a class <strong>Student </strong>with the above attributes and following member functions:




<ul>

 <li><strong>Setter and Getter Functions for of all the attributes. </strong></li>

</ul>

<strong> </strong>

<ul>

 <li><strong>CompleteProgram: </strong>This member function takes the program type and the student id as input arguments and returns <strong>true</strong> if the student has finished all the courses by comparing the completed credits with the required credit for the program that the student is enrolled in.The function returns false if the program is not completed.

  <ul>

   <li>Bachelor: 140 credit</li>

   <li>Master: 16</li>

   <li>D: 12</li>

  </ul></li>

</ul>




<ul>

 <li><strong>StudentStatus (): </strong>This function takes the GPA as an input argument and returns the status as below:

  <ul>

   <li>if GPA&gt;=3.5 returns A+</li>

   <li>if GPA in the range of 3 (inclusive) -3.5: A</li>

   <li>if GPA in the range of 2.5(inclusive) – 3: B</li>

   <li>if GPA in the range of 2(inclusive) – 2.5: C</li>

   <li>Less than 2: D</li>

  </ul></li>

</ul>




<ul>

 <li><strong>Print_Std_Info() </strong>: This function accepts the id of one student and prints out all the information of that student (all the attributes).</li>

</ul>




<ul>

 <li><strong>Comapre_GPA(): </strong>This function compares the GPA of two students and returns the id of the student who has the higher GPA.</li>

</ul>




–




<strong>Part 2: Faculty Class: </strong>

<strong> </strong>

Assume the faculty of engineering has three departments: electrical and computer engineering, mechanical engineering and civil engineering.

You need to implement this class to read the input files and create the arrays of students for different departments of the faculty of engineering.




<strong>Attributes: </strong>a pointer to an array of students of electrical and computer engineering  a pointer to an array of students of mechanical engineering a pointer to an array of students of civil engineering




<strong>Constructor(): </strong>

Reads <strong>student_elec_comp.tx</strong>t file and creates a dynamic array of electrical and computer engineering students

Reads <strong>student_mech.txt</strong> file and creates a dynamic array for mechanical engineering students

Reads <strong>student_civil.txt</strong> file and creates a dynamic array for civil engineering students




<strong>Member functions: </strong>

<strong> </strong>

<strong>Highest_GPA: </strong>This function accepts an array of students and its size, then prints out the information of the one who has the highest GPA

<strong>N_of_UnderGrad</strong>: This function accept an array of students, and its size and returns the total number of undergraduate students.

<strong>N_of_Grad</strong>: This function accept an array of students, and its size and returns the total number of graduate students.

<strong>Avg_UnderGrad</strong>: This function accept an array of students and its size, and returns the average of GPA of undergraduate students.

<strong>Avg_Grad</strong>: This function accept an array of students, and its size and returns the average of GPA of graduate students.

<u>                                                                                                                                                                 </u>–




<strong>Part 3: </strong>Driver:




<ol>

 <li>In the driver you will test your system. You first create an object of <strong>Faculty</strong> class</li>

</ol>

to be able to read the input files and create your student arrays. Then you need to test the member functions of the <strong>faculty</strong> Class and show the results.

<ol>

 <li>To test the functions in the <strong>Student</strong> class, you can manually create the student objects and call different functions for this class.</li>

</ol>




<strong>Note</strong>: You need to store the information of at least <strong>five</strong> students in your input files (<em>studenst.txt</em>)








