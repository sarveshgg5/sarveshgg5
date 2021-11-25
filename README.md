def compute(x,y):
    if x>y:
        smaller = y
        smaller = x
    for i in range(1,smaller + 1):  
          if((x % i == 0) and (y % i == 0)):
              gcd = i
    return gcd 
num1 = 34
num2 = 24
print("GCD is",compute(num1,num2))
