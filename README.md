# Biling-system-for-supermarketwhile True:
    name = input("enter customer name: ")
    total = 0

    while True :
        print ("enter the amount and quantity ")
        amount = float(input("enter amount: "))
        quantity = float(input("enter quantity: "))
        total += amount * quantity 
        repeat = input("do you want to add more item? (yes/no): ")
        if repeat == "no" or repeat == "No":
            break
    print("-" * 40 )
    print("Name : ", name )
    print("amount to be paid: ", total)
    print("-" * 40 )
    print("****happy shopping****") 

    repeat1 = input("do you want to go next customer? (yes/no): ")
    if repeat1 == "no" or repeat == "NO":
            break
