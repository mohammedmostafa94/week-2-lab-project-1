# week-2-lab-project-1
water_per_loaf=1.5
yeast_per_loaf=1.0
flour_per_loaf=4.5
oil_per_loaf=2.0
num_of_loaves=int(input("How many loaves do you want to make? "))
water_needed=round(water_per_loaf * num_of_loaves, 1)
yeast_needed=round(yeast_per_loaf * num_of_loaves, 1)
flour_needed=round(flour_per_loaf * num_of_loaves, 1)
oil_needed=round(oil_per_loaf * num_of_loaves, 1)
print(f"You need {water_needed} cups of warm water, {yeast_needed} tablespoons of yeast, {flour_needed} cups of all-purpose flour, and {oil_needed} tablespoons of oil.")
