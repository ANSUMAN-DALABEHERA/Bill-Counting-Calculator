# Bill-Counting-Calculator
This is my first project 
<br>
total = 0
count = 0

print("Enter prices (type 0 to stop)")

price = int(input("Enter price: "))

while price != 0:
    total = total + price
    count = count + 1
    price = int(input("Enter price: "))

average = total / count

print("Total Bill:", total)
print("Average:", average)
