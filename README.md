# Marksheet.Python
Create a Marksheet using Python
print("Enter the marks of five subjects")

Maths= int(input("Enter the maths marks ="))
Phys= int(input("Enter the physics marks ="))
Oops= int(input("Enter the Oops marks ="))
Eng= int(input("Enter the English marks ="))
Chem= int(input("Enter the Chemistry marks ="))

Total = (Maths + Phys + Oops + Eng + Chem)

Percentage = (Total/500)*100

print("Your Percentage is =",Percentage)

if (Percentage >=90) :
    print( "Grade 'A*'")
elif (Percentage >= 80) :
    print("Grade 'A'")
elif (Percentage >= 70):
    print("Grade 'B'")
elif (Percentage >= 60):
    print("Grade 'C'")
elif (Percentage >= 50):
    print("Grade 'D'")
else :
    print("Parhlo ! Wrna koi baap apni beti nhin dega !")


