>>> id(a)
139926795932424
>>> a
[1, 2, 3, 4]
>>> a = a + [5]
>>> id(a)
28. Same or not?
28-answer.txt: Will the last line of this script print 139926795932424?
>>> a
[1, 2, 3]
>>> id (a)
139926795932424
>>> a += [4]
>>> id(a)
29. #pythonic

100-magic_string.py: Python function magic_string() that returns the string "BestSchool" n times the number of iteration.
30. Low memory cost

101-locked_class.py: Python class LockedClass with no attributes that prevents the user from dynamically creating any new instance attributes not called first_name.
31. int 1/3

103-line1.txt: How many int objects are created by the execution of the first line in this script?
104-line2.txt: How many int objects are created by the execution of the second line in this script?
a = 1
b = 1
32. int 2/3
104-line1.txt: How many int objects are created by the execution of the first line in this script?
104-line2.txt: How many int objects are created by the execution of the second line in this script?
104-line3.txt: After the execution of line 3, is the int object pointed to by a deleted?
104-line4.txt: After the execution of line 4, is the int object pointed to by b deleted?
104-line5.txt: How many int objects are created by the execution of the last line in this script?
a = 1024
b = 1024
del a
del b
c = 1024
33. int 3/3
105-line1.txt: Before the execution of line 2 in this script, how many int objects have been created and are still in memory?
print("I")
print("Love")
print("Python")


34. Clear strings
106-line1.txt: How many str objects are created by the execution of the first line in this script?
106-line2.txt: How many str objects are created by the execution of the second line in this script?
106-line3.txt: After the execution of line 3, is the str object pointed to by a deleted?
106-line4.txt: After the execution of line 4, is the str object pointed to by b deleted?
106-line5.txt: How many str objects are created by the execution of the last line in this script?
a = "SCHL"
b = "SCHL"
del a
del b
c = "SCHL"
