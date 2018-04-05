# This repositiry is protected by Apache License 2.0

Assuming you are in the directory containing this README:

## To clean:
ant -buildfile src/build.xml clean

-----------------------------------------------------------------------
## To compile: 
ant -buildfile src/build.xml all

-----------------------------------------------------------------------
## To run by specifying arguments from command line 
ant -buildfile src/build.xml run -Darg0=FIRST -Darg1=SECOND -Darg2=THIRD

-----------------------------------------------------------------------

Data Structures used in terms of Big O complexity (time and/or space)

int[] array for storing input from file:
Array is fized size data structure. We do not need to constantly modify our integer array since we increase it half more each time. But if we need to, then we need to make a new one and copy all the elements from previous array. This operation is costly.
Big O Time complexity:O(n)
Big O Space complexity:O(n)

ArrayList<String> for storing results:
ArrayList is not fixed size, hence we can modify it more frequently when needed.Storing results needs constant change in size of the list according to the test cases.Even if we set an initial size, we can still modify the size
Big O Time complexity:O(n) under normal circumstances

-----------------------------------------------------------------------

List of citations

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

6. Print arrayList elements
Referred to: https://stackoverflow.com/questions/9265719/print-arraylist

7. Compare two results during testCases
Referred to: https://stackoverflow.com/questions/20631621/cannot-find-symbol-assertequals
