# Project-3
Gradebook (Use of 1 and 2d Lists and modifying those lists)
last_semester_gradebook = [["politics", 80], ["latin", 96], ["dance", 97], ["architecture", 65]]

# Your code below: 
subjects = [ "physics", "calculus", "poetry", "history"]
grades = [98, 97, 85, 88]
#Create 2/d list
gradebook = [["physics",98], ["calculus", 97],["poetry", 85], ["history", 88]]

#print(gradebook)
#append
new_grades1 = ["computer science", 100]
gradebook.append (new_grades1)
#print(gradebook)
#2nd append
new_grades2 = ["visual arts", 93]
gradebook.append (new_grades2)
#print adding points to grade (indexing)
gradebook [-1][-1] = 98
#removing score
gradebook[2].remove (85)
#Add a pass fail option
gradebook[2].append ("Pass")
#create a new gradebook with the previous semester contained
full_gradebook = last_semester_gradebook + gradebook
print (full_gradebook)
