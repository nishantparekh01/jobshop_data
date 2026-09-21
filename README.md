This repository contains commonly used benchmark instances for the Job Shop Scheduling Problem (JSSP).

Included instances currently include:

ft06
ft10
ft20
la01 – la20

The original format of each test problem is something like:
+++++++++++++++++++++++++++++
instance ft06
+++++++++++++++++++++++++++++
Fisher and Thompson 6x6 instance, alternate name (mt06)
6 6
2 1 0 3 1 6 3 7 5 3 4 6
1 8 2 5 4 10 5 10 0 10 3 4
2 5 3 4 5 8 0 9 1 1 4 7
1 5 0 5 2 5 3 3 4 8 5 9
2 9 1 3 4 5 5 4 0 3 3 1
1 3 3 3 5 9 0 10 4 4 2 1

In the above table, 6 6 means the problem has a 6 x 6 dimension. In the first row you see 12 numbers. Each
pair of two numbers represents machine process order and processing time respectively, for each job on its
corresponding line. For example, the first line corresponds to the first job, and the values are
2 1 0 3 1 6 3 7 5 3 4 6 which mean the first operation of job 1 is done on machine 2 with duration 1, the
second operation is done on machine 0 with duration 3, the third operation is done on machine 1 with
duration 6 and so on.
