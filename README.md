# armstrong
n = float(input("Enter a number: "))
s = 0
t = n
t > 0
t!= float(n)
while t>0:  
   digit = t % 10
   s += digit ** 3
   t //= 10
if n<0 :
  print("It is an invalid entry. Don't use non-numeric, float, or negative values!")
if t==float(n) :
  print("It is an invalid entry. Don't use non-numeric, float, or negative values!")
if n == s:
   print(n,"is an Armstrong number")
else:
   print(n,"is not an Armstrong number")
