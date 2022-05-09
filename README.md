# 09-05-22-ass-2
#write a program to retrieve email id with the name using dictionary.(bases HackeRank program)
n=int(input("enter a number:"))
d={}
for i in range(n):
    x=input().split()
    d[x[0]]=x[1]
while True:
    try:
       EMAIL=input() 
       if EMAIL in d:
          print(EMAIL,"=",d[EMAIL],sep=" ")
       else:print("not found")
    except:
        break
        
        
output:
enter a number:3
janu jahnavisigireddy@gmail.com
veda vedanjalikontikalapudi@gmail.com
deepu jandeep3021@gmail.com
veda
veda=vedanjalikontikalapudi@gmail.com
