# customer-experience-index-in-
Python  calculate customer experience index in 
a = int(input("Enter the total number of customers who have purchased your products: "))
b = int(input("Enter the number of customers who have purchased your products and were satisfied: "))
c = int(input("Enter the total number of customers whose orders were delivered on time: "))
d = int(input("Enter the total number of orders that were delivered on time: "))
e = int(input("Enter the total number of customers who have recommended your products due to their quality: "))
f = int(input("Enter the total number of customers who have purchased your products and recommended them to others due to their quality: "))
g = int(input("Enter the total number of complaints you have received: "))
h = int(input("Enter the total number of orders you have received: "))
i = int(input("Enter the total number of customers who have repurchased your products: "))
j = int(input("Enter the total number of customers who were satisfied with your products: "))

cei = ((a/b) + (c/d) + (e/f) + (g/h) + (i/j)) / 5

print("Customer Experience Index: {:.2f}".format(cei))
