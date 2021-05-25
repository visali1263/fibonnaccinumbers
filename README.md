# fibonnaccinumbers
done for my captain course project using python looping

num = int(input("Enter the value of 'n': "))
num1 = 0
num2 = 1
sum = 0
count = 1
print("Fibonacci Series: ", end = " ")
while(count <= num):
  print(sum, end = " ")
  count += 1
  num1 = num2
  num2 = sum
  sum = num1 + num2
