#TO DO LIST 
l=[]

def view():
    for i in l:
        print(i, end="\n")

def add():
    ans="yes"
    while ans=='yes': 
          task=input("Enter your task: ")
          l.append(task)
          ans=input("Do you wish to continue adding tasks? yes/no: ")

def done():
    ans="yes"
    while ans=='yes': 
        t2=input("Enter the task you want to mark as done: ")
        l.remove(t2)
        ans=input("Do you wish to continue marking tasks? yes/no: ")
        
print("----------------------❁ WELCOME TO YOUR TO DO LIST!❁-----------------------")

while True:
    print("MENU \n1.View your list \n2.Add tasks \n3.Cross off tasks \n4.To exit")  
    ch=int(input("Enter your choice: "))
    if ch==1: 
        view()
    elif ch==2:
        add()
    elif ch==3:
        done()
    elif ch==4:
        break
    else:
        print("Sorry! Invalid choice")
