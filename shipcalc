weight = 41.5

## Ground Shipping ##
ground_flat = 20
prem_ground = 125
cost_ground = ""

print("Ground Shipping Premium: $",prem_ground)

if weight <= 2:
    cost_ground = weight * 1.5 + 20
elif weight > 2 and weight <= 6:
    cost_ground = weight * 3 + 20
elif weight > 6 and weight <= 10:
    cost_ground = weight * 4 + 20
elif weight > 10:
    cost_ground = weight * 4.75 + 20
else:
    print("Please enter package weight.")

print("Total Ground Cost: ", cost_ground)


## Drone Shipping ##
cost_drone = ""

if weight <= 2:
    cost_drone = weight * 4.5
elif weight > 2 and weight <= 6:
    cost_drone = weight * 9
elif weight > 6 and weight <= 10:
    cost_drone = weight * 12
elif weight > 10:
    cost_drone = weight * 14.25
else:
    print("Please enter package weight.")

print("Total Drone Cost: $" , cost_drone)
