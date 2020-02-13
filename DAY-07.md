## Statement
## Write a program that reads an integer number and prints its previous and next numbers. See the example below.

Example input
179

Example output
The next number for the number 179 is 180
The previous number for the number 179 is 178


Theory
If you don't know how to start solving this assignment, please, review a theory for this lesson:
https://snakify.org/lessons/print_input_numbers/

You may also try step-by-step theory chunks:
https://snakify.org/lessons/print_input_numbers/steps/1/

```
# Read an integer:
a = int(input())
b= a+1
c= a-1
# Print a value:
print('The next number for the number' +str(a)+ 'is' +str(b))
print('The previous number for the number' +str(a)+ 'is' +str(c))
```
