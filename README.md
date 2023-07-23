# PlayPiano
# cook your dish here
t=int(input())
while t:
    x=(input())
    for i in range(0,len(x),2):
        if x[i]==x[i+1]:
            print("no")
            break
    else:
        print("yes")
    t-=1
