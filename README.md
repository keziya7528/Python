# Python
Basic concepts in Python
income=float(input("please enter your income"))/100000
if income >0 and income <=3:
    print("s1")
    tax = income*0
elif income >3and income <=6:
    print("s2")
    tax = (income-2.5)*(5/100)
elif income >6 and income <=9:
    print("s3")
    tax = (income-5)*(20/100)+2.5*(5/100)
elif income >9 and income <=12:
elif income >12 and income <=15:
elif income >15:    
    print("s4")
    tax = (income-10)*(30/100)+5*(20/100)+2.5*(5/100)
print(int(tax*100000))    
    
