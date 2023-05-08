Download Link: https://assignmentchef.com/product/solved-solvedprogram-called-diff-py-solution
<br>
1. Write a program called diff.py that asks the user for two files and displays the differences between the characters in each file.1. Your program should ask the user for the path to two different files2. For every character that is in the same position in each file but is different between the two files your program should display the index of those characters (starting from 0) as well as the value of those two characters.3. If one file is longer than the other your program should report the index of each of the characters as well as the fact that it could not find a matching character4. Examples:1. Assume ex1.txt contains the contents: “batman” and ex2.txt contains the contents bitman” and ex3.txt contains the contents “backmans”.1. Enter the name of the first file: ex1.txtEnter the name of the second file: ex2.txtMismatch at character 1 a != i2. Enter the name of the first file: ex2.txtEnter the name of the second file: ex1.txtMismatch at character 1 i != a3. Enter the name of the first file: ex1.txtEnter the name of the second file: ex3.txtMismatch at character 2 t != cMismatch at character 3 m != kMismatch at character 4 a != mMismatch at character 5 n != aMismatch at character 6!= nNo matching character for character 7 (s) found inex3.txt.No matching character for character 8 () found in ex3.txt.4. Enter the name of the first file: ex3.txtEnter the name of the second file: ex1.txtMismatch at character 2 c != tMismatch at character 3 k != mMismatch at character 4 m != aMismatch at character 5 a != nMismatch at character 6 n !=No matching character for character 7 (s) found inex3.txt.No matching character for character 8 () found in ex3.txt.2. For this problem you will be creating a program called grading.py that takes a directorycontaining files that record how student’s performed on their assignments and from these files determines each students grades in addition to the course statistics.1. You can only import the os module for this problem1. If you import any other modules you will receive a 0 on this problem2. Your program should ask the user for the directory that contains the homework files3. Homework files1. The name of a homework file is arbitrary2. Each file is stored as csv and and has the following format1. Percent Total, Percent contribution this assignment has to the student’s grade,2. Max Points,Maximum number of points on the assignment,3. ,,4. Last Name,First Name,Grade5. Student 1 Last Name, Student 1 First Name, Student 1’s Grade6. Student 2 Last Name, Student 2 First Name, Student 2’s Grade7. …3. Percent Total across all files will sum to 1004. The names in the homework file are stored in arbitrary order4. Your program should output the course statistics base on each student’s percentage in the class1. The mean2. Median1. We will continue to use the same median as used in homework 33. Mode1. There will always be a unique mode4. Uncorrected sample standard deviation1. Def: √ 1NΣi=1N( xi−̄x)22. N: The number of items3. xi : The value of item I4. ̄x: the mean5. After displaying the course statistics your program should display each student’s percent grade in the class as well as their letter grade1. Grades should be displayed in alphabetical order based on last name1. If two people have the same last name then the ordering is based on their first names2. For computing the letter grades1. A’s = 90%2. B’s = 80% and &lt; 90%3. C’s = 70% and &lt; 80%4. D’s = 60% and &lt; 70%5. F’s &lt; 60%6. You must use functions in this assignment. Your program must have at least the following functions. You’re free to have more than just these functions if you desire1. mean1. returns the mean of the given numbers2. median1. returns the middle value of the given numbers. We are doing a simplified version where we always take the middle number.3. mode1. returns the most commonly occurring number in the given numbers4. std_dev1. returns the uncorrected sample standard deviation of the given numbers5. percent2Letter1. given a percentage grade return the letter grade associated with it6. read_homework1. reads in 1 homework file and returns or updates the students scores on theassignment, the number of points that assignment is worth, and the percentcontribution that it makes to the students overall grades7. display_statistics1. This should display the course statistics2. This function is partially completed for you. Please make sure to use the provided format strings so that your output matches mine8. display_grades1. This should display the students grades in alphabetical order.2. This function is partially completed for you. Please make sure to use the provided format strings so that your output matches

Example:◦ Tests/Test1 only contains HW1.csv◦ HW1.csv contains the following:Percent Total,100,Max Points,50,,,Last Name,First Name,GradeSmith,John,50Fruit,Apple,43Dog,Lab,25Cat,Long,36Smith,Will,13Veg,Carrot,50Please enter the name of the directorycontaining the homeworks: Tests/Test1Mean | Median | Mode | Standard Deviation72.33 | 86.00 | 100.00 | 26.97Last Name | First Name | Percent | LetterCat | Long | 72.00 | CDog | Lab | 50.00 | FFruit | Apple | 86.00 | BSmith | John | 100.00 | ASmith | Will | 26.00 | FVeg | Carrot | 100.00 | A