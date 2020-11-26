# Python-program-to-find-out-whether-a-student-is-pass-or-fail-
This is a python program to find out whether a student has passed an exam or failed, if it requires 33% to pass less than 33% is fail and at 75% pass while more than 75% is excellent. 
 # Please like if you like it:
 # Here is the program: 
 a = int(input("Enter your marks here:\n"))
if a>=75:
    print("Congratulation you have passed the exam, You are a very good Student!!!")
elif (a<75 and a>33):
    print("You are passed!!!")
elif a==33:
    print("You are barely passed in the exam, try improve your concepts !!!")    
elif a<33 and a>=1:
    print("You are failed in the Exam") 
elif a==0:
    print("You need a lots of improvement, by the way you are failed in the exam.")     

print("Thank You")   
