# fibonacci-series
printing fibonacci series
a= 0
b= 1
sum = 0
count = 1
print("fibonacci series :", end = " " )
while(count <= 5):
   print(sum,end = " ")
   count += 1
   a = b
   b = sum 
   sum = a + b
   
 output:
 fibonacci series : 0 1 1 2 3
