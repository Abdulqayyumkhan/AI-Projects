# AI-Projects
#Student Marksheet creater
english_marks=eval(input("Enter marks of english:"))
urdu_marks=eval(input("Enter marks of urdu:"))
maths_marks=eval(input("Enter marks of maths:"))
islamiat_marks=eval(input("Enter marks of islamiat:"))
pakstudies_marks=eval(input("Enter marks of pakstudies_marks:"))
obtained_marks=eng_marks+urdu_marks+maths_marks+islamiat_marks+pakstudies_marks
total_marks=500
percentage=((obtained_marks/total_marks)*100)
print("percentage=",percentage)
if(percentage>=80 and percentage<=100):
    print("Your Grade is A+")
elif(percentage>=70 and percentage<80):
    print("Your Grade is A")
elif(percentage>=60 and percentage<70):
    print("Your Grade is B")
elif(percentage>=50 and percentage<60):
    print("Your Grade is C")
elif(percentage>=40 and percentage<50):
    print("Your Grade is D")
else:
    print("Your Grade is F")
