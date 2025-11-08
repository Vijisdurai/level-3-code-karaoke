
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/cf9296ba-8410-4592-8df0-bac4afd7fdba" />

# Level-3-code-karaoke
Level 3 questions for code karaoke event, there are 2 scenario based  fork and upload in git hub 

# 1st Question :
1.You are building a billing system for a small café.
The café sells:
•	Coffee → ₹60
•	Sandwich → ₹120
•	Cake → ₹80
You need to write a Python program that:
1.	Asks the user what they want to order.
2.	Asks how many of that item they want.
3.	Calculates and displays the total bill.

# Code:
```
items = {'coffee':60,"sandwich":120,"cake":80}
a=input("what you want ?? ")
b=int(input("quantity ?? "))
print(items.get(a)*b)
```
# OUTPUT:
<img width="1443" height="101" alt="image" src="https://github.com/user-attachments/assets/3c2c22af-b709-4d8b-b33d-335980042759" />


# Question 2:
2. You’re designing a program for a college portal that evaluates a student’s final grade based on their marks in 3 subjects.
Rules:
•	If the average is 90 or above → Grade A+
•	If the average is 75–89 → Grade A
•	If the average is 60–74 → Grade B
•	If the average is 40–59 → Grade C
•	Below 40 → Fail
The program should:
1.	Take marks for 3 subjects from the user
2.	Calculate the average
3.	Print the average and the grade
________________________________________
# Example Input / Output:
Enter mark for Subject 1: 85
Enter mark for Subject 2: 78
Enter mark for Subject 3: 90
Average = 84.33
Grade = A





# Code:
```
a=int(input())
b=int(input())
c=int(input())
avg=(a+b+c)/3
print(avg)
if(avg>90):
    print ("a+")
elif(avg>75 and avg < 89):
    print("a")    
elif(avg>60 and avg< 74):
    print("b")
elif (avg>40 and avg< 59):
    print ("c")
else:
    print("fail")
```

# OUTPUT:
![WhatsApp Image 2025-11-08 at 11 24 15_c41c0cdb](https://github.com/user-attachments/assets/722abe9d-ea4a-48c5-97e6-e4ac08bf1727)
