Q1. Why do we call Python as a general purpose and high-level programming language?

    Ans:Python is a general purpose language,and it is broadly applicable across application domain rather than particular application domain.And also python is contrary to domain specific language(DSL).
        python is high level programming language because of easy coding and also to solve different types of problems.

Q2. Why is Python called a dynamically typed language?
    
    Ans:Pyton is a dynamically typed language.basically in normal type the variable do have a type to perform operation using the variable,but in dynamic type the type of variable automatically interprets the type and it can be determined only in the runtime.

Q3. List some pros and cons of Python programming language?

    Ans:Pros:
            1.easy syntax format
            2.versatility
            3.variety of libraries
        Cons:
            1.heavy memory usage
            2.slow speed    

Q4. In what all domains can we use Python?

    Ans: Artificial intelligence
         Machine learning and deep learning
         Used as tool for data scientist
         Database

Q5. What are variable and how can we declare them?

    Ans:A variable is name assigning to an object,whenever we want to use an object we can simply call the variable to access the value stored in it.and it is declare in  variable=10 .

Q6. How can we take an input from the user in Python?

    Ans:The input() fn is used to get user's input.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

    Ans: the default datatype in input() is "string".

Q8. What is type casting?

    Ans:Type casting means changing one data type to another datatype.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

    Ans:yes it can be used
         
         a, b, c = input("Enter the values: ").split(",")
         print("value of a: ", a)
         print("value of b : ", b)
         print("value of c : ", c)
         print()

Q10. What are keywords?

    Ans:Python keywords are special reserved words that have specific meanings and purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.

    Ans:No, we cannot use keywords as a variable.

Q12. What is indentation? What's the use of indentaion in Python?

    Ans:Indentation refers to the spaces in python.it is used to indicate the blocks in the statement.

Q13. How can we throw some output in Python?

    Ans:print() fn.

Q14. What are operators in Python?

    Ans:operators in python are used to perform some operations.

Q15. What is difference between / and // operators?

    Ans:/ is for float division
        // is for integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

    Ans:print("Inueron"*3)
    
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

    Ans:
         num = float(input("Enter a number: "))
         if num%2 == 0:
            print("even")
        else:
            print("odd")

Q18. What are boolean operator?

    Ans:True
        False
        And
        Or
        Not

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Q20. What are conditional statements in Python?

    Ans:Conditional statements in python is the condition is stated to be satisfied,if it is satisfied only the execution of program will run,it not satisfied it will not run.

Q21. What is use of 'if', 'elif' and 'else' keywords?

    Ans:"if" is not satisfied elif will execute
        "elif" is not satisfied else will execute
        "else" will execute if and elif fails

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

    Ans:age = int(input("Enter your age: "))
        if age >= 18:
             print("voter")
        else:
             print("Non voter") 

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
`
Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
add=0
for num in numbers:
  if num%2 == 0:
    add = add+num
  else:
    continue
print(add)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Ans:
a, b, c = int(input("Enter three numbers: ")).split(",")
if (a>b) and (a>c):
  print("a is greatest")
elif b>c:
  print("b is greatest")
else:
  print("c is greatest")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Ans:
numbers = [12, 75, 150, 180, 145, 525, 50]
lst = []
for num in numbers:
    if num >150:
      if num>500:
       break
    elif num%5==0:
        lst.append(num) 

print(lst)

       output[75,150,145]


Q26. What is a string? How can we declare string in Python?

Ans:A string is a normally considered as a datatype and implemented as words.
    In python,sting can be declared using ' ," ,'''

Q27. How can we access the string using its index?

Ans:To access the string,string name followed by square bracket [].

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```

Ans:
string = "Big Data iNeuron"
print ('"',string[9:16],'"')

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```

Ans:
string = "Big Data iNeuron"
print ('"',string[15:8:-1],'"')

Q30. Resverse the string given in the above question.

Ans:string[::-1]

Q31. How can you delete entire string at once?

Ans:
    string="hai"
    del(string)

Q32. What is escape sequence?

Ans:An escape character is a backslash "\" followed by the character you want to insert.To insert characters that are illegal in a string, use an escape character.An example of an illegal character is a double quote inside a string that is surrounded by double quotes:

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
Ans:
print('iNeuron\'s Big Data Course')

Q34. What is a list in Python?

Ans:List is nothing but an array,in list we can use integer, float datatype in a square bracket [] seperated by comma ,

Q35. How can you create a list in Python?

Ans:crate list by using opening and closing square bracket [].

Q36. How can we access the elements in a list?

Ans:access the element in the list by indexing.

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 

Ans:
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst [4][2])

Q38. Take a list as an input from the user and find the length of the list.

Ans:
list1=input("enter number of elements in the list seperate with space:").split(" ")
print(len(list1))

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```

Ans:
    lst = ["Welcome", "to", "Data", "course"]
    lst.insert(2,"big")

Q40. What is a tuple? How is it different from list?

Ans:Tuple is a collection of Python objects much like a list.In tuple we can add element while running the code, The sequence of values stored in a tuple can be of any type, and they are indexed by integers. Tuples are immutable where as list are mutable.

Q41. How can you create a tuple in Python?

Ans:We can create tuple using round brackets ().

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Ans:we can't add to tuple because it is immutable,we can do it by typecasting tuple into list and append the name.

ex:
tup1=()
tup1=list(tup1)
tup1.append("thiru")
tup1=tuple(tup1)
print(tup1)

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Ans:yes,two tupple can be appended

tup1=("thiru ")
tup2=("pugal")
tup3=( )
tup3=tup1+tup2
print(tup3)


Q44. Take a tuple as an input and print the count of elements in it.

Ans:
a = input("Enter the values separeted by space: ").split(" ")
a = tuple(a)
print(len(a))

Q45. What are sets in Python?

Ans:sets in python is an unordered collection of data types that is iterable, mutable, it removes duplicate values and provide distinct values.

Q46. How can you create a set?

Ans:sets can be created using parantheses {} .it should have some values in the set otherwise it will be considered as dictionary.

Q47. Create a set and add "iNeuron" in your set.

Ans:
set={"ineuron"}
print(set)

Q48. Try to add multiple values using add() function.

Ans:
set={"ineuron"}
set.add("name")
print(set)

Q49. How is update() different from add()?

Ans: We can add more than one element in a single go using update(), but using add() it's not possible.

Q50. What is clear() in sets?

Ans: clear() function is used to remove all the elements from the set.

Q51. What is frozen set?

Ans: Frozen sets in Python are immutable objects that only support methods and operators that produce a result without affecting the frozen set or sets to which they are applied. While elements of a set can be modified at any time, elements of the frozen set remain the same after creation. 

Q52. How is frozen set different from set?

Ans:
- Frozen sets are immutable where as sets are mutable.
- Sets can't be used as keys in dictionary where as frozen sets can be used.

Q53. What is union() in sets? Explain via code.


Ans: Python set Union() Method returns a new set which contains all the items from the original set.

set1 = {2, 4, 5, 6}
set2 = {4, 6, 7, 8}
set3 = {7, 8, 9, 10}
print("set1 U set2 : ", set1 | set2)
print("set1 U set2 U set3 :", set1 |set2 | set3)

Q54. What is intersection() in sets? Explain via code.

Ans: Python set intersection() method returns a new set with an element that is common to all set

set1 = {1,2,3,4}
set2 = {1,3,2,4}
set3 = {5,7,6}
print("set1 intersection set2 : ", set1.intersection(set2))
print("set1 intersection set2 intersection set3 :", set1.intersection(set2, set3))

Q55. What is dictionary ibn Python?

Ans: Dictionary in Python is a collection of keys values, used to store data values like a map, which, unlike other data types which hold only a single value as an element.

Q56. How is dictionary different from all other data structures.

Ans: Dictionary is having key and value pair where as all other data structures have only values in them.

Q57. How can we delare a dictionary in Python?

Ans: We can create dictionary using curly brackets {}.

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
Ans: dict

Q59. How can we add an element in a dictionary?

Ans: 
Dict = {}
Dict[0] = "Hello"
Dict[1] = "Course: ["Data Science", "Big Data"]"


Q60. Create a dictionary and access all the values in that dictionary.

Ans:

Dict = {"Name": "thiru", "Experience": 3, "Organisation":"iNeuron"}
for i, j in Dict.items():
  print(f"Key is {i} and value is {j}")


Q61. Create a nested dictionary and access all the element in the inner dictionary.

Ans:
Dict = {"Name": {"f_name":"thiru", "l_name":"pugal"}, "Experience": 3, "Organisation":"iNeuron"}
for i, j in Dict["Name"].items():
  print(f"Key is {i} and value is {j}")

Q62. What is the use of get() function?

Ans:  get() is also to access the elements in dictionary.

Dict = {"Name": "thiru"}
print(Dict.get("Name"))


Q63. What is the use of items() function?

Ans: items() method is used to return the list with all dictionary keys with values.

Dict = {"Name": "thiru", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.items())

Q64. What is the use of pop() function?

Ans:

Dict = {"Name": "thiru", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.pop("Name"))

Q65. What is the use of popitems() function?

Ans: popitem() method removes the last inserted key-value pair from the dictionary and returns it as a tuple.

Dict = {"Name": "thiru", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.popitem())

Q66. What is the use of keys() function?

Ans:  keys() method returns a view object that displays a list of all the keys in the dictionary.

Dict = {"Name": "thiru", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.keys())

Q67. What is the use of values() function?


Ans: values() is an inbuilt method in Python programming language that returns a view object. The view object contains the values of the dictionary, as a list.

Dict = {"Name": "thiru", "Experience": 3, "Organisation":"iNeuron"}
print(Dict.values())


Q68. What are loops in Python?

Ans: Loops are used the iterate over a block of statement multiple times.

Q69. How many type of loop are there in Python?

Ans: There is for and while loop in Python

Q70. What is the difference between for and while loops?

Ans: When we know the exact number of iterations, we can use for loop. When we want the to run till a certain condition is true we can use while loop.

Q71. What is the use of continue statement?

Ans: Continue Statement skips the execution of the program block from after the continue statement and forces the control to start the next iteration.

Q72. What is the use of break statement?

Ans: break statement in Python is used to bring the control out of the loop when some external condition is triggered. break statement is put inside the loop body

Q73. What is the use of pass statement?

Ans: The pass statement is a null statement. But the difference between pass and comment is that comment is ignored by the interpreter whereas pass is not ignored. 

Q74. What is the use of range() function?

Ans: range() function returns a sequence of numbers, in a given range. The most common use of it is to iterate sequence on a sequence of numbers

Q75. How can you loop over a dictionary?

Ans:

statesAndCapitals = {
	'Gujarat': 'Gandhinagar',
	'Maharashtra': 'Mumbai',
	'Rajasthan': 'Jaipur',
	'Bihar': 'Patna'
}

for state in statesAndCapitals:
	print(state)



### Coding problems

Q76. Write a Python program to find the factorial of a given number.

Ans:
num=int(input("enter the number to factorize"))

def factorial(num):

    if num==0 or num==1:
        return 1

    result=1
    for num in range(1,num+1):
        result=result*num
    return result
result=factorial(num)
print("the factorial for",num,  " is " , result)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

Ans:

def simple_interest(p,r,t):

    si=p*r*t/100
    print(f'simple interest is {si}')
    return si

simple_interest(3000,7,1)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Ans:

def compound_interest(p,r,t):

    A = p*(1+ r/100)**t
    ci=A-p
    print(f'compound interest is {ci}')
    

compound_interest(3000,5,3)

Q79. Write a Python program to check if a number is prime or not.

Ans:

from math import sqrt

def prime_num(n):
  prime_flag = 0

  if(n > 1):
    for i in range(2, int(sqrt(n)) + 1):
      if (n % i == 0):
        prime_flag = 1
        break
    if (prime_flag == 0):
      print(f"{n} is a prime number.")
    else:
      print(f"{n} is not a prime number.")
  else:
    print(f"{n} is not a prime number.")

prime_num(67)


Q80. Write a Python program to check Armstrong Number.

Ans:
def check_armstrong(n):
  s = n
  b = len(str(n))
  sum1 = 0
  while n != 0:
      r = n % 10
      sum1 = sum1+(r**b)
      n = n//10
  if s == sum1:
      print(f"The given number {s} is armstrong number")
  else:
      print(f"The given number {s} is not armstrong number")

check_armstrong(100)

Q81. Write a Python program to find the n-th Fibonacci Number.

Ans:
def Fibonacci(n):
	if n<= 0:
		print("Incorrect input")
	elif n == 1:
		return 0
	elif n == 2:
		return 1
	else:
		return Fibonacci(n-1)+Fibonacci(n-2)

print(Fibonacci(7))

Q82. Write a Python program to interchange the first and last element in a list.

Ans:

def swap_list(newList):
     
    newList[0], newList[-1] = newList[-1], newList[0]
 
    return newList
     
newList = [15, 12, 35, 17, 9, 56, 29]
print(swap_list(newList))

Q83. Write a Python program to swap two elements in a list.

Ans:
def swapPositions(list, pos1, pos2):
	
	list[pos1], list[pos2] = list[pos2], list[pos1]
	return list

List = [15, 12, 35, 17, 9, 56, 29]
pos1, pos2 = 1, 3

print(f"Original list: {List}")
print(f"Swapped list: {swapPositions(List, pos1, pos2)}")

Q84. Write a Python program to find N largest element from a list.

Ans:
def n_max_elements(list1, N):
	final_list = []

	for i in range(0, N):
		max1 = 0
		
		for j in range(len(list1)):	
			if list1[j] > max1:
				max1 = list1[j];
				
		list1.remove(max1);
		final_list.append(max1)
		
	print(final_list)

list1 = [2, 6, 41, 85, 0, 3, 7, 6, 10]
N = 3

n_max_elements(list1, N)

Q85. Write a Python program to find cumulative sum of a list.

Ans:
def cumulative_sum(lists):
	cu_list = []
	length = len(lists)
	cu_list = [sum(lists[0:x:1]) for x in range(0, length+1)]
	return cu_list[1:]

lists = [10, 20, 30, 40, 50]
print(f"Cumulative sum of the list is {cumulative_sum(lists)}")

Q86. Write a Python program to check if a string is palindrome or not.

Ans:

def isPalindrome(s):
  if s == s[::-1]:
	  return f"{s} is palindrome"
  return f"{s} is not palindrome"

s = "dad"
isPalindrome(s)

Q87. Write a Python program to remove i'th element from a string.

Ans:

def remove_ith_element(i):
  str1 = "Big Data Bootcamp"
  str2 = ""

  for n in range(len(str1)):
    if n == i:
      continue
    else:
      str2 = str2 + str1[n]

  return str2

remove_ith_element(5)

Q88. Write a Python program to check if a substring is present in a given string.

Ans:

def check_substring(s2, s1):
	if (s2.count(s1) > 0):
		print(f'"{s1}" is a substring of "{s2}"')
	else:
		print(f'"{s1}" is not a substring of "{s2}"')


s2 = "Welcome to iNeuron Big Data Bootcamp"
s1 = "iNeuron"
check_substring(s2, s1)

Q89. Write a Python program to find words which are greater than given length k.

Ans:

def string_greater_than_k(k, str):
	
	string = []

	text = str.split(" ")

	for x in text:

		if len(x) > k:

			string.append(x)

	return string

k = 3
str ="Big Data Bootcamp"
print(string_greater_than_k(k, str))

Q90. Write a Python program to extract unquire dictionary values.

Ans:
test_dict = {'iNeuron': [5, 6, 7, 8],
			'is': [10, 11, 7, 5],
			'best': [6, 12, 10, 8],
			'for': [1, 2, 5],
      'big data': [2, 7, 12, 9]
      }

print("The original dictionary is : " + str(test_dict))

res = list(sorted({ele for val in test_dict.values() for ele in val}))

print("The unique values list is : " + str(res))

Q91. Write a Python program to merge two dictionary.

Ans:

def Merge(dict1, dict2):
	return(dict2.update(dict1))

dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}

print(Merge(dict1, dict2))

print(dict2)


Q92. Write a Python program to convert a list of tuples into dictionary.
```python
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
Ans:

print (dict([('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]))


Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```python
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
Ans:

list1 = [9, 5, 6]

res = [(val, pow(val, 3)) for val in list1]

print(res)


Q94. Write a Python program to get all combinations of 2 tuples.
```python
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
Ans:

test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

res = [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res + [(a, b) for a in test_tuple2 for b in test_tuple1]

print("The filtered tuple : ", str(res))


Q95. Write a Python program to sort a list of tuples by second item.
```python
Input : [('452', 10), ('256', 5), ('100', 20), ('135', 15)]
Output : [('256', 5), ('452', 10), ('135', 15), ('100', 20)]
```
Ans:


def Sort_Tuple(tup):
     
    lst = len(tup)
    for i in range(0, lst):
         
        for j in range(0, lst-i-1):
            if (tup[j][1] > tup[j + 1][1]):
                temp = tup[j]
                tup[j]= tup[j + 1]
                tup[j + 1]= temp
    return tup
 
tup =[('452', 10), ('256', 5), ('100', 20), ('135', 15)]
       
print(Sort_Tuple(tup))

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
Ans:


def pypart(n):
	
	for i in range(0, n):
	
		for j in range(0, i+1):
		
			print("* ",end="")
	
		print("\r")

n = 5
pypart(n)


Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
Ans:
def inverse_pattern():
  n=5;i=0
  while(i<=n):
    print(" " * (n - i) +"*" * i)
    i+=1

inverse_pattern()

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
Ans:

def triangle(n):
	
	k = n - 1

	for i in range(0, n):

		for j in range(0, k):
			print(end=" ")
	
		k = k - 1
	
		for j in range(0, i+1):

			print("* ", end="")
	
		print("\r")

n = 5
triangle(n)


Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
Ans:

def numpat(n):

	num = 1

	for i in range(0, n):

		num = 1

		for j in range(0, i+1):

			print(num, end=" ")

			num = num + 1

		print("\r")

n = 5
numpat(n)


Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
Ans:

def alphapat(n):

	num = 65

	for i in range(0, n):
	
		for j in range(0, i+1):

			ch = chr(num)
		
			print(ch, end=" ")
	
		num = num + 1
	
		print("\r")

n = 5
alphapat(n)
