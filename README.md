# 22-02-2022
Assignment -2
n=int(input())
for i in range (1,n+1):
    for k in range (n-i,0,-1):
        print (' ',end=' ')
    for j in range (1,i+1):
        print('*',end='   ')
    print('\n')
for i in range (2,n+1):
    for k in range (1,i):
        print (' ',end=' ')
    for j in range (n-i+1,0,-1):
        print('*',end='   ')
    print('\n')
