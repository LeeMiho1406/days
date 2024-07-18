Annual=int(input())
Calender=int(input())
match Calender:
    case 1:
        Calender= 1
        print("31 Days")
    case 2:
        Calender= 2
        print("29 Days")
        if(Annual%4==1):
            print("28 Days")
    case 3:
        Calender= 3
        print("31 Days")
    case 4:
        Calender= 4
        print("30 Days")
    case 5:
        Calender= 5
        print("31 Days")
    case 6:
        Calender= 6 
        print("30 Days")
    case 7:
        Calender= 7
        print("31 Days")
    case 8:
        Calender= 8
        print("31 Days")
    case 9:
        Calender= 9
        print("30 Days")
    case 10:
        Calender= 10
        print("31 Days")
    case 11:
        Calender= 11
        print("30 Days")
    case 12:
        Calender= 12
        print("31 Days")
    case _:
        Calender>=13
        print("Invalid Input")
