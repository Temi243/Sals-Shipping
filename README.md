# Sals-Shipping

weight = 1.5
#Ground Shipping 

if weight <= 2:
  ground_cost = weight * 1.5 + 20
elif 2 < weight <= 6:
  ground_cost = weight * 3 + 20
elif 6 < weight <= 10:
  ground_cost = weight * 4 + 20
else:
  ground_cost = weight * 4.75 + 20

#Ground Premium Shipping
prem_cost = 125.00


#Drone Shipping
if weight <= 2:
  drone_cost = weight * 4.5
elif 2 < weight <= 6:
  drone_cost = weight * 9 
elif 6 < weight <= 10:
  drone_cost = weight * 12
else:
  drone_cost = weight * 14.25 

print(drone_cost)
