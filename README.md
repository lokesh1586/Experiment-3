# Experiment-3

## NAME: Dheena Darshini Karthik Dheepan
## REGNO: 212223240030

## PRIME NUMBER OR NOT

# Aim: Write a python program to check the number is prime or not and inspect for failures. 

# Algorithm
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
 - If the number is divisible by the current iteration value, return "Not Prime".
6. If the number is not divisible by any value from 2 to the square root, return "Prime".
7. Stop the program. 

## Program
```
num = input("Enter a number: ")  
flag = 0  

if num.isnumeric():  
    z = int(num)  

    if z == 2:  
        flag = 1  
    elif z > 2:  
        for i in range(2, z // 2 + 1):  # Loop should include z//2
            if z % i == 0:  
                flag = 0  
                break  
        else:  
            flag = 1  

    if flag == 1:  
        print("Prime Number")  
    else:  
        print("Not a Prime Number")  

else:  
    print("Enter a Positive Number")
```
## Output

![Screenshot 2025-03-22 111656](https://github.com/user-attachments/assets/a1a94c55-1afb-4aea-a934-294b5dffff30)

![Screenshot 2025-03-22 111715](https://github.com/user-attachments/assets/8d0a05aa-37ca-4572-9a89-a838be9107c1)

![Screenshot 2025-03-22 111816](https://github.com/user-attachments/assets/591a2841-3bbc-46fb-b1f6-642bbe6bea7f)

![Screenshot 2025-03-22 111831](https://github.com/user-attachments/assets/f77fb5b8-5f60-4262-9a8b-e72f8cb7c380)

![Screenshot 2025-03-22 111843](https://github.com/user-attachments/assets/a7a79499-e98a-4d7f-a5bb-eb80dcb79cc3)

![Screenshot 2025-03-22 111856](https://github.com/user-attachments/assets/f54b48ec-79d9-40fb-8313-5fc066c03124)




## Result
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
