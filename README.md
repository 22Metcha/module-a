for i in range(10):
    print("Hello Python!")


import random 


print ("Random number from 0 to 9 is : ",end="") 
print (random.choice([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])) 


print ("Random number from 1 to 10 is : ",end="") 
print (random.choice([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])) 

print ("Even number from 2 to 20 is : ",end="")
print (random.choice([2, 4, 6, 8, 10, 12, 14, 16, 18, 20]))

def printValues():
	l = list()
	for i in range(1, 10):
		l.append(i**2)
	print(l)
		
printValues()

