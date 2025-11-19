# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212222060025
# Name-Bharath S

a=int(input())
b=int(input())
c=int(input())
if (a<b and a<c):
    print(f"The Smallest  of the three a= {a} b= {b} c= {c} is {a}")
elif(b<a and b<c):
    print(f"The Smallest  of the three a= {a} b= {b} c= {c} is {b}") 
else:
    print(f"The Smallest  of the three a= {a} b= {b} c= {c} is {c}") 
```

## OUTPUT
<img width="1182" height="398" alt="Screenshot_1" src="https://github.com/user-attachments/assets/5a4276c2-777b-4d24-8b17-ae1b65d07334" />


## RESULT
Thus the Python program to find the minimum between three integer numbers using a conditional expression was successfully written and executed.
