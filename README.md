# Python-clculator
#This is a simple calculator made using python.
import time
try:
    while True:#loop
        
        a = input("First number: ")
        a = int(a)
        o = input("Operation( + or - or / or * ):")
        b = input("Second number: ")
        b = int(b)

        if o == "+":
            print("Ok! ",a,"+",b,"=",a+b)

        elif o == "-":
            print("Ok! ",a,"-",b,"=",a-b)

        elif o == "/":
            print("Ok! ",a,"/",b,"=",a/b)

        elif o == "*":
            print("Ok! ",a,"x",b,"=",a*b)

        else:
            print("Invalid operation")

        time.sleep(2)
        print("")
        print("")

finally:
    print("Ok! ")
