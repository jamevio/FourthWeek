# FourthWeek
Time complexity /// Using Java 
Q1: Why can't we rely on CPU execution time to measure algorithm efficiency?

A: Because all CPU's are built different with varying capabilities to the executions they can do in the unit time. Some CPU's are 2.4 GHz, some are 3 GHz and some are faster than that. A CPU with 3 GHz speed can execute a program in 0.3 seconds while a CPU with 2.4 GHz can execute it in 0.8 seconds.

Q2: How many operations does this code execute?
"int sum = 0;
 sum = sum + 5"

 A: The first line is one operation, and the second line is an operation also, therefore it executes two operations.
 O(1)

 Q3: Give the final time complexity of the code:

 a) "int sum = 0;                   b) "int sum = 0 ;                           c) "int n = 1024;
     for (int i = 0; i < n; i++)        for (int i = 0; i <n; i++){                 int count = 0;
        sum += i;"                          for (int j = 0; j < n; j++ ){           while (n > 1){
                                                sum += i+j;                             n = n / 2;
                                            }                                           count++;
                                        }"                                              System.out.println("n="+n);
                                                                                    }
                                                                                    System.out.println("Total divisions:" + count);"
 

A.a: O(n)
A.b: O(n^2)
A.c: O(logn)
