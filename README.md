# Python-Week-1

# Introduction to Python:

- How are files store on a computer memory == in blocks
- To access the file location we can use a pointer to the location of the file
- Files can be stored as 'Text files - Strings or characters, Integers, Floats, Hexadecimal'
- A file name has to have a specific data type before is stored on the memory of a computer
- File names are reffered to as variables, and they can either be declared empty or initialised a value
- Computer machines uses what is reffered to as a pseudocode to read and execute programs (Algorthm)
- This a summury of how a Computer thinks

# How to install python and run it on your machine:
- For one to be abale to run a python program on their machines they must have a python Extension/Software installed
- Installing Jupyter Notebook, which is a web based IDE to run python codes, and we can also run a python code on the terminal
- We can also use a text editor like Vs Code. to run python code, to edit or modify our codes

# Variables and types:

- Vars in python just like in any other programming language can be integer, floating point, strings of char, boolean
- These are the data types a variable cann take before it is stored on the computer memory
- Every variable must be correctly asigned to its correct data type to avoid errors
- Vars in python just like in any other programming language can be integer, floating point, strings of char, Boolean
- Every variable must be correctly assigned to its correct data type to avoid errors

# Example:

- print (”Hello world!”) #Working with strings
- x = 7 #integer value
- y = 8.0 #Double/ float
- print (x + y) #Adding float and int

# Tuple

Grade = 50, 34, 78, 38, 75, 75

type(Grade)

# List comprehension
1. list = [5,8,5,7,6,912,21,50,60]
2. 
3. even_list = [x for x in list if x % 2 ==0] # To get numbers that are even and divisible by 2
4. Odd_list = [x for x in list if x % 2 != 0 ] # Odd numbers in the list
5. 
6. #print (even_list)
7. #print (Odd_list)
8. 
9. new = [x/2 if x % 2 == 0 else 2*x for x in list ]
10. print (new)
 
# Dictionaries
- Are accessed using a keys, does not allow duplicates
- Changeable, ordered
- To check whether you have a list, set or a tuple you can use the function ‘type(My_list)’ for example if you have the function My_list

1. company = {
2. 
3.   "name" : "CapaCiTi",
4.   "Workers" : 5,
5.   "Age" : 1960
6. }
7.
8. print(company.get("name"))
9.
10. company.popitem() #Remove the last item added to the Dictonary
11. print (company)

# Nested Dictionary

1. candidate1 = {
2. "name" : "Mtiza",
3. "Age" : 30,
4. "Work" : "CapaCiTi"
5. }
6. 
7. candidate2 = {
8.   "name" : "Melz",
9.   "Age" : 40,
10.  "Work" : "CapaCiTi"
11. }
12. 
13. candidate3 = {
14. "name" : "Lorrane",
15. "Age" : 20,
16. "Work" : "CapaCiTi"
17. }
18. 
19. MyCandidates = {
20. 
21.    "candidate1" : candidate1,
22.    "candidate2" : candidate2,
23.    "candidate3" : candidate3
24. }
25. 
26. print(MyCandidates.get("candidate1"))

# Dictioanary comprehension

Book_prices = { #in Dolla

    "Maths" : 50,
    "Accounting" : 35,
    "Geography" : 67,
    "Science" : 92
}

zar = 00.62

Selling = {k: r for k, r in Book_prices.items()}
print(Selling)

#Convert to Rand

Selling = {k: r*zar for k, r in Book_prices.items()}
print("This are the book prices in Rands" ,Selling)

# Control flow

Control flows are used to perform actions only when a certain condition is met, unless otherwise.

#If statement
if len(ArdaCiti) <= 5:

    print ("First person on the list is:", ArdaCiti[0])
    
#If – else statement
ArdaCiti = ['Lindelani', 'George', 'Mesuli', 'Nolu', 'Zanda']

if 'Lindelani' in ArdaCiti:  #Using the If statement
    
    print("Lindelani is part of the group")

else:
    print("He's not part of the group") #Else statement if condition 

#For loop
for Nolu in ArdaCiti:

    print ("Group stays active")
    break
    
#While loop
while len(ArdaCiti) < 5:

    print ("Group is normal")
    break
    
# Function
- Functions takes input and produces output
- A functions can be given a set of instructions
- In python, functions can be defined using the ‘def’ command
- Every function must have a function name, arguments which are optional, and the function body
