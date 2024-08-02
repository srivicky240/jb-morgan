parked_car=[]
def park():
    car=(input("enter the car number:"))
    parked_car.append(car)
    print ("car parked")

def remove():
    car_remove=(input("enter the car number:"))
    if car_remove in parked_car:
        parked_car.remove(car_remove)
        print("car removed")
    else:
        print("car not found")

def list():
    a=len(parked_car)
    print ("No of parked car:",a)
    print("car numbers",parked_car)

i=0
while i<4:
 i=i+1
 print(" \n1 parking")
 print("2 remove")
 print("3 list parked car")
 print("4 exit")
 choice=(input("Enter your choice:"))
 if choice=="1":
    park()
 elif choice=="2":
    remove()
 elif choice=="3":
    list()
 elif choice=="4":
    print("thank you")
    break
 else:
    print("enter the choice correctly")

print ("parking full")

