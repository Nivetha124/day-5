# day-5


num=len(input())
count1 = 1
count2 = 2
if num==1:
    print(num)
if num==2:
    print(num)
else:
    for i in range(0,num-3):
        count1, count2=count2,count1+count2
print(count1+count2)
