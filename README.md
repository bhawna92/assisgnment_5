# assisgnment_5

In first task we have a dictionary of 3 students with name alice, john and cena 
when user is asked to select the student , their marks are printed and if student is not found in dictionary message"not found" is printed
#dictionaries
dict1={'alice':85,'john':65,'cena':90}
name = input("Enter the student name: ")
print(dict1.get(name,"not found"))

In second task, we have a list from number 1 to 10 and for printing first five values  index 0 :5 is used
or for printing the reverse of above result , reversed function is used
#LIST
list1=[1,2,3,4,5,6,7,8,9,10]
print("original list:",list1)
print("extracted first 5 items:",list1[0:5])
print("reversed first 5 items:",list(reversed(list1[0:5])))
