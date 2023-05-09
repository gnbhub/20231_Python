Ex1
```py
#ex1

Num=[]

for i in range(0,10) :
    Num.append(int(input("두 자리 수 입력 : ")))

Num.reverse()

print(Num)
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/61dd5b69-4714-4b76-b360-9fb557fa5471)

Ex2
```py
#ex2
M_List =[-2,3,7,10,-13,-6,8,-5,17,-10,5,-2]
Loti=0
temp1=0
temp2=0

for i in range(0,len(M_List)) :
    temp1= temp1 + M_List[i]

    if temp1>temp2 :
        temp2=temp1
        Loti=i

    else :
        pass
print(M_List,end='')
print("라는 리스트인 경우에는 %d번째 숫자인 %d까지 합한 결과 %d이 최대값입니다." %(Loti+1,M_List[Loti],temp2))
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/60ddd238-3185-48ba-9671-b87c3b204bae)

ex3
```py
#ex3

M_list=[]
temp=0

for i in range(0,7) :
    M_list.append(int(input("숫자를 입력하세요 : ")))

M_list.sort()
M_list.reverse()

print(M_list[1])
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/d918d427-f7e8-4aff-8fb1-97c93517cd15)
