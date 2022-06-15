# github-test
text = input('Enter a string: ')
count1= 0
count2= 0

for i in text:
    if (i.isupper()):
       count1=count1+1
    elif(i.islower()):
       count2= count2+1
print("the number of uppercase is:")
print(count1)
print("the number of lowercase is:")        
print(count2)
