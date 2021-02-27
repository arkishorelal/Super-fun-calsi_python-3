v=1
p=0
k="yes"
n="no"
o=input("Enter your name: \t")
print("\n\nHi !",o,"welcome to kishore's calculator")
def addition():
        print("addition")
        print("\n\nenter number [0] to stop addtion")
        b=int(input("\n\nenter a first number to add : \t"))
        c=int(input("\n\nenter a second number to add : \t"))
        d=b+c
        print("the addition of two numbers is",d)
        print("\n\nExcited?, do you add more numbers   please Enter(yes/no)")
        n=input()
        if(n=="esc"):
                global y
                y=y+1
                if(y==0):
                        print("thank you")
        if(n=="yes"):
                k=input("Do you want to continue with alreadly added number ? enter (yes/no)")
                if(k!=n):      
                     while (v>p):
                            m=int(input("\n\nenter a number to add : \t"))
                            if(m==0):
                                 break
                                 print("thankyou")
                            n=int(input("\n\nenter a second number to add : \t"))
                            
                            l=n+m
                            print("\nthe added values are - \t",l)
                            if(l==0):
                                 break
                            print("thankyou")
                elif(k==n):
                     while(d>=v):
                        f=int(input("\n\nenter a number to add : \t"))
                        d=d+f
                        print("\nthe added values are - \t",d)
                        if(f==0):
                            break
                else:
                    print("then go for subtraction")
            
                    
def subtraction():
      
        print("subtraction")
        b=int(input("\nenter a first number to sub : \t"))
        c=int(input("\nenter a second number to sub : \t"))
        d=b-c
        print("the addition of two numbers is",d)
        print("\n\nExcited?, do you sub more numbers   please Enter(yes/no)")
        print("\n\nenter number [0] to stop subtraction")
        n=input()
        if(n=="esc"):
                global y
                y=y+1
                if(y==0):
                        print("tq")
        if(n=="yes"):
                k=input("Do you want to continue with alreadly subtracted number ? enter (yes/no)")
                if(k!=n):      
                     while True:
                            m=int(input("\n\nenter a number to subtraction : \t"))
                            if(m==0):
                                 break
                                 print("thankyou")
                            n=int(input("\n\nenter a second number to subtraction : \t"))
                            l=m-n
                            print("\nthe subtraction values are - \t",l)
                                
                            
                elif(k==n):
                     while True:
                        f=int(input("\n\nenter a number to subtraction : \t"))
                        d=d-f
                        print("\nthe subtraction values are - \t",d)
                        if(f==0):
                            break
                else:
                     print("then go for subtraction")
            
        
def multiplication():
      
        print("multiplication")
        b=int(input("\nenter a first number to multiplication : \t"))
        c=int(input("\nenter a second number to multiplication : \t"))
        d=b*c
        print("the multiplication of two numbers is",d)
        print("\n\nExcited?, do you multiply more numbers   please Enter(yes/no)")
        print("\n\nenter number [0] to stop multiplication")
        n=input()
        if(n=="esc"):
                global y
                y=y+1
                if(y==0):
                        print("thank you")
        if(n=="yes"):
                k=input("Do you want to continue with alreadly multiplied number ? enter (yes/no)")
                if(k!=n):      
                             while (v>p):
                                    m=int(input("\n\nenter a number to multiplication : \t"))
                                    if(m==0):
                                       break
                                       print("thankyou")
                                    n=int(input("\n\nenter a second number to multiplication : \t"))
                                    
                                    l=n*m
                                    print("\nthe multiplication values are - \t",l)
                                    if(l==0):
                                         break
                                    print("thankyou")
                elif(k==n):
                             while(d>=v):
                                f=int(input("\n\nenter a number to multiplication : \t"))
                                d=d*f
                                print("\nthe multiplication values are - \t",d)
                                if(f==0):
                                    break
                else:
                    print("then go for division")
            
       
def division():
      
        print("division")
        b=int(input("\nenter a first number to division : \t"))
        c=int(input("\nenter a second number to division : \t"))
        d=b/c
        print("the division of two numbers is",d)
        print("\n\nExcited?, do you divide more numbers   please Enter(yes/no)")
        print("\n\nenter number [0] to stop division")
        n=input()
        if(n=="esc"):
                global y
                y=y+1
                if(y==0):
                        print("thank you")
        if(n=="yes"):
                k=input("Do you want to continue with alreadly divided number ? enter (yes/no)")
                if(k!=n):      
                             while True:
                                    m=int(input("\n\nenter a number to division : \t"))
                                    if(m==0):
                                         break
                                         print("thankyou")
                                    n=int(input("\n\nenter a second number to division : \t"))
                                    
                                    l=n/m
                                    print("\nthe division values are - \t",l)
                                    if(l==0):
                                         break
                                    print("thankyou")
                elif(k==n):
                             while True:
                                f=int(input("\n\nenter a number to divisionn : \t"))
                                d=d/f
                                print("\nthe division values are - \t",d)
                                if(f==0):
                                    break
                else:
                    print("then go for mod")
            
        
def mod():
      
        print("mod")
        b=int(input("\nenter a first number to mod : \t"))
        c=int(input("\nenter a second number to mod : \t"))
        d=b%c
        print("the mod of two numbers is",d)
        print("\n\nExcited?, do you mod more numbers?  please Enter(yes/no)")
        print("\n\nenter number [0] to stop mod")
        n=input()
        if(n=="esc"):
                global y
                y=y+1
                if(y==0):
                        print("thank you")
        if(n=="yes"):
                k=input("Do you want to continue with alreadly modded number ? enter (yes/no)")
                if(k!=n):      
                             while (v>p):
                                    m=int(input("\n\nenter a number to mod : \t"))
                                    if(m==0):
                                         break
                                         print("thankyou")
                                    n=int(input("\n\nenter a second number to mod : \t"))
                                    
                                    l=n%m
                                    print("\nthe mod values are - \t",l)
                                    if(l==0):
                                         break
                                    print("thankyou")
                elif(k==n):
                             while(d>=v):
                                f=int(input("\n\nenter a number to mod : \t"))
                                d=d%f
                                print("\nthe mod values are - \t",d)
                                if(f==0):
                                    break
            
       
            
while True:
        z=()
        print("\n\nfor addition type letter [a] : \t")
        print("\n\nfor subtraction type letter [b] : \t")
        print("\n\nfor multiplication type letter [c] : \t")
        print("\n\nfor division type letter [d] : \t")
        print("\n\nfor mod type letter [e] : \t")
        print("\n\nenter [q] for quit")
        c=input(" ")
        if(c=='a'):
            z=addition()
            print(z)
        if(c=='b'):
            p=subtraction()
            print(p)
        if(c=='c'):
            q=multiplication()
            print(q)
        if(c=='d'):
            e=division()
            print(e)
        if(c=='e'):
            g=mod()
            print(g)
        if(c=='q'):
            print("thankyou for running")
            break
        
    
