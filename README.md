# identifer-checker
#This program check whether a give string is a valid indentifer according to python naming rules  

import time
user_name=("Saba unissa")
age=21
def check_eligibilty(age):
    if age>=18:
        return(" eligible for driving licesnse")
    else:
     return(" not eligible for driving licesnse")
    eligiblity=check_eligibilty(age)
print()
print("user name:",user_name)
print("age:",(age))
print("eligiblity=check_eligibilty(age):",(age))
print()
time.sleep(3)
print("end of an application")
