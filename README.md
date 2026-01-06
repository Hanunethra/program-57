# program-57

numbers=[4,2,7,1,8,3,6]
f=0
x=int(input("enter the number  to be found out:"))
for i in range(len(numbers)):
    if(x==numbers[i]):
        print("successful search, the element is found at position",i)
        f=1
        break
if(f==0):
    print("oops!search unsuccessful")
            

Output:

enter the number  to be found out:3
successful search, the element is found at position 5

