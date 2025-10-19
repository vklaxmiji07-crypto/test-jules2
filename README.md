# test-jules2
print('''
     ! =============================== !
     !   Welcome to Grocery Store      !
     ! =============================== !
     !item no.  !  Item Name !  Price  !
     !0         !  aloo      !    $2   !
     !1         !  began     !   $20   !
     !2         ! cauliflower!   $10   !
     !3         !  dhokla    !   $40   !
     !4         ! eggplant   !   $20   !
     ! =============================== !
''')
#input no. for item and quantity
#Input item
item = input("Enter item no. to add to the basket ( range = 0, 1, 2, 3, 4): ")
#Input quantity
Quantity = input("Enter number of items to add to the basket (range = 0, 1,2,3,4):  ")
#list-
list = [1, 2, 3, 4, 5]
list2 = ['aloo', 'began', 'cauliflower', 'dhokla', 'eggplant']
price_of_item = [2, 20, 10, 40, 20]
#print the output
print("loading your basket...")
delay = 2
import time
time.sleep(delay)
print("Your basket is ready!")
print("===================================")
print(f"There are {str(list[int(Quantity)]) + ' ' + list2[int(item)]} in the basket.\n Total price is ${str(list[int(Quantity)] * price_of_item[int(item)])}\n Thank you for shopping with us! Visit again!\n===================================")    
