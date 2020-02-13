## Statement
## Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.

Example input #1
1
1
1
2
2
2

Example output #1
3661

Example input #2
1
2
30
1
3
20

Example output #2
50

Theory
If you don't know how to start solving this assignment, please, review a theory for this lesson:
https://snakify.org/lessons/print_input_numbers/ 

You may also try step-by-step theory chunks:
https://snakify.org/lessons/print_input_numbers/steps/1/

```
hour1 = int(input())
minute1= int(input())
second1= int(input())
hour2= int(input())
minute2= int(input())
second2= int(input())
h=(hour2 - hour1)*3600
m=(minute2 - minute1)*60
s=(second2 - second1)
print(h+m+s)
```
