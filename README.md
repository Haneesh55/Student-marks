# Student-marks
n=int(input())
a=list(map(int,input().strip().split()))
for i in range(n):
    if a[i]>=38 and a[i]<=100:
        if a[i]%5==0:
            print(a[i])
        else:
            if (a[i]+1)%5==0:
                print(a[i]+1) 
            else:
                if (a[i]+2)%5==0:
                    print(a[i]+2)
                else:
                    print(a[i])    
    else:
         print(a[i])
