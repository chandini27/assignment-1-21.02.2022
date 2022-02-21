# assignment-1-21.02.2022
Display aScii  values  in pattern 
n=int(input('enter number:'))
ascii_value=97
for i in range(1,n+1):
    for j in range(1,n+1):
        print(chr(ascii_value),end=" ")
        ascii_value+=1
    print("\n")
Output
Enter number:4
A b c d
E f g h 
I j k l
M n o p
