# This program calculates the value of each menu and calculates the total stock
# The menu list, number of stock and the price are listed  
menu = ['chips', 'fish', 'chicken', 'burger']
stock = {'chips': 15, 'fish': 6, 'chicken': 7, 'burger': 8}
price = {'chips': 2, 'fish': 8, 'chicken': 4, 'burger': 3}
print("Items value:")
total_cost = 0
#seting the items as keys
for item in menu:
    item_cost = stock[item] * price[item]
    total_cost += item_cost
    print(item, "-", item_cost,"Pounds")
print("The total stock:", total_cost,"Pounds")


