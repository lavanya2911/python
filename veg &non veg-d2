def calculate_bill_amount(food_type,quantity_ordered,distance_in_kms):
    bill_amount=0
    #write your logic here
    if(food_type=="N"):
        bill_amount=150*quantity_ordered
        if(distance_in_kms>3 and distance_in_kms<7):
            bill_amount=(bill_amount)+((distance_in_kms-3)*3)
        elif(distance_in_kms>6):
            bill_amount=(bill_amount)+(3*3)+((distance_in_kms-6)*6)
    elif(food_type=="V"):
        bill_amount=120*quantity_ordered
        if(distance_in_kms>3 and distance_in_kms<7):
            bill_amount=(bill_amount)+((distance_in_kms-3)*3)
        elif(distance_in_kms>6):
            bill_amount=(bill_amount)+(3*3)+((distance_in_kms-6)*6)
    if((food_type!="N" and food_type!="V") or quantity_ordered<1 or distance_in_kms<=0):
        bill_amount=-1
    return bill_amount

#Provide different values for food_type,quantity_ordered,distance_in_kms and test your program
bill_amount=calculate_bill_amount("N",2,7)
print(bill_amount)
