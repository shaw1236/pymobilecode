# nodemobilecode

Mobile text code utilities

# Installation of the package

$pip install pymobilecode-shaw1236

# Usage of class MobileCode in code

from pymobilecode.MobileCode import MobileCode

mobileCode = MobileCode()

#Add the phone list

for phone in ["6172201234", "9051234567", "9087654321"]:

    mobileCode.add(phone)

#Show all the codes

print("Here are the code list:")

mobileCode.list()
