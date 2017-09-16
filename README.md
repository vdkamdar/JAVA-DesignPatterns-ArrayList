
Assuming you are in the directory containing this README:

## To clean:
ant -buildfile src/build.xml clean

-----------------------------------------------------------------------
## To compile: 
ant -buildfile src/build.xml all

-----------------------------------------------------------------------
## To run by specifying arguments from command line 
## We will use this to run your code
ant -buildfile src/build.xml run -Darg0=FIRST -Darg1=SECOND -Darg2=THIRD

-----------------------------------------------------------------------

## To create tarball for submission
ant -buildfile src/build.xml tarzip or tar -zcvf firstName_secondName_assign_number.tar.gz firstName_secondName_assign_number

-----------------------------------------------------------------------

"I have done this assignment completely on my own. I have not copied
it, nor have I given my solution to anyone else. I understand that if
I am involved in plagiarism or cheating I will have to sign an
official form that I have cheated and that this form will be stored in
my official university record. I also understand that I will receive a
grade of 0 for the involved assignment for my first offense and that I
will receive a grade of F for the course for any additional
offense.”

[Date: 15/09/2017]

-----------------------------------------------------------------------

Provide justification for Data Structures used in this assignment in
term of Big O complexity (time and/or space)

int[] array for storing input from file:
Array is fized size data structure. We do not need to constantly modify our integer array since we increase it half more each time. But if we need to, then we need to make a new one and copy all the elements from previous array. This operation is costly.
Big O Time complexity:O(n)
Big O Space complexity:O(n)

ArrayList<String> for storing results:
ArrayList is not fixed size, hence we can modify it more frequently when needed.Storing results needs constant change in size of the list according to the test cases.Even if we set an initial size, we can still modify the size
Big O Time complexity:O(n) under normal circumstances

-----------------------------------------------------------------------

Provide list of citations (urls, etc.) from where you have taken code
(if any).

1. Format String output using toString
Referred to: https://stackoverflow.com/questions/26576909/how-to-format-string-output-so-that-columns-are-evenly-centered

2. Read file line by line
Referred to: https://rosettacode.org/wiki/Read_a_file_line_by_line#Java

3. Deciding data structures Array v/s ArrayList
Referred to: http://www.geeksforgeeks.org/array-vs-arraylist-in-java/

4. Analysed different methods to write to file
Referred to: http://www.baeldung.com/java-write-to-file

5. Solving nullPointerException
Referred to: https://stackoverflow.com/questions/26334397/nullpointerexception-during-file-io

6. How to print arrayList elements
Referred to: https://stackoverflow.com/questions/9265719/print-arraylist

7. Compare two results during testCases
Referred to: https://stackoverflow.com/questions/20631621/cannot-find-symbol-assertequals
