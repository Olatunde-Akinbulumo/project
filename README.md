# This program calculates the value of each menu and calculates the total stock

menu = ['chips', 'fish', 'chicken', 'burger']
# The menu and their quantity
stock = {'chips': 15, 'fish': 6, 'chicken': 7, 'burger': 8}
#The menu and their unit price
price = {'chips': 2, 'fish': 8, 'chicken': 4, 'burger': 3}
print("Items value:")
total_cost = 0
#seting the items as keys
for item in menu:
    item_cost = stock[item] * price[item]
    total_cost += item_cost
    print(item, "-", item_cost,"Pounds")
print("Total_stock:", total_cost,"Pounds")

