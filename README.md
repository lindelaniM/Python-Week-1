# Python-Week-1

Introduction to Python:

> How are files store on a computer memory, in blocks
> To access the file location we can use a pointer to the location of the file
> Files can be stored as 'Text files - Strings or characters, Integers, Floats, Hexadecimal'
> A file name has to have a specific data type before is stored on the memory of a computer
> File names are reffered to as variables, and they can either be declared empty or initialised a value
> Computer machines uses what is reffered to as a pseudocode to read and execute programs (Algorthm)
> This a summury of how a Computer thinks

> How to install python and run it on your machine:
> For one to be abale to run a python program on their machines they must have a python Extension/Software installed
> Installing Jupyter Notebook, which is a web based IDE to run python codes, and we can also run a python code on the terminal
> We can also use a text editor like Vs Code. to run python code, to edit or modify our codes

Variables and types:

> Vars in python just like in any other programming language can be integer, floating point, strings of char, boolean
> These are the data types a variable cann take before it is stored on the computer memory
> Every variable must be correctly asigned to its correct data type to avoid errors
> Vars in python just like in any other programming language can be integer, floating point, strings of char, Boolean
Every variable must be correctly assigned to its correct data type to avoid errors
Example:

print (“”Hello world!”)
x = 7
y = 8.0
print (x + y)

# Tuple

Grade = 50, 34, 78, 38, 75, 75

type(Grade)

# List comprehension
list = [5,8,5,7,6,912,21,50,60]

even_list = [x for x in list if x % 2 ==0] # To get numbers that are even and divisible by 2
Odd_list = [x for x in list if x % 2 != 0 ] # Odd numbers in the list

#print (even_list)
#print (Odd_list)

new = [x/2 if x % 2 == 0 else 2*x for x in list ]
print (new)

#Dictionary
#Accessed using a keys, does not allow duplicates
#Changeable, ordered
#To check whether you have a list, set or a tuple you can use the function ‘type(My_list)’ for example if you have the function My_list

company = {

    "name" : "CapaCiTi",
    "Workers" : 5,
    "Age" : 1960
}

#print(company.get("name"))

# def calculator():

    #print("I do maths better")

# calculator()

company.popitem() #Remove the last item added to the Dictonary

print (company)

# Nested Dictionary

candidate1 = {
 "name" : "Mtiza",
 "Age" : 30,
 "Work" : "CapaCiTi"
}

candidate2 = {
    "name" : "Melz",
    "Age" : 40,
    "Work" : "CapaCiTi"
}

candidate3 = {
 "name" : "Lorrane",
 "Age" : 20,
 "Work" : "CapaCiTi"
}

# MyCandidates = {

    "candidate1" : candidate1,
    "candidate2" : candidate2,
    "candidate3" : candidate3
}

print(MyCandidates.get("candidate1"))

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

# Function
Functions takes input and produces output
.A functions can be given a set of instructions
.In python, functions can be defined using the ‘def’ command
.Every function must have a function name, arguments which are optional, and the function body
