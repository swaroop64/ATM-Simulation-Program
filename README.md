# Functionality-of-ATM

#ATM
'''
What do we need for an ATM?
1.Credit
2.Debit
3.Mini statement
4.Exit'''

atm='''
1.Credit
2.Debit
3.Mini statement
4.Exit
'''               #string format

Amount = 500
user="Swaroop"
pin=1234
user_name=input("Enter your name:")
pins=int(input("Enter your PIN:"))
if user==user_name and pin==pins:
    while True:
        print(atm)
        option=int(input("Enter a choice:"))
        if option==1:
            credit_amount=float(input("Enter the credit amount:"))
            print("Total amount after credit:",Amount+credit_amount)
        elif option==2:
            debit_amount=float(input("Enter the debit amount:"))
            if Amount < debit_amount:
                print("Insufficient Funds")
            else:
                print("Total amount after debit:",Amount-debit_amount)
        elif option==3:
            print("###MINI STATEMENT### \n Total amount available in your account:",Amount)
        elif option==4:
            print("Thank you🙏 \nVisit Again")
            break
else:
    print("Incorrect Credentials")
