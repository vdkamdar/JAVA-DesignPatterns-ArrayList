# JAVA-DesignPatterns-ArrayList #

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

