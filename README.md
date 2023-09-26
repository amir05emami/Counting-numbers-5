# Counting-numbers-5
a=int(input('num_1: '))
b=int(input('num_2: '))
five_counter=0
for i in range(a,b+1):
    for x in str(i):
        if x=='5':five_counter+=1
print(five_counter)
