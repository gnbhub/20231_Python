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

Ex4
```py
#ex4

List1=[1,571,7,11,20005,16]
List2=[134,5,23,1090]

List1.extend(List2)

List1.sort()
List1.reverse()

print(List1)
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/08e8ba64-e5bf-496d-944b-26ddeb54b512)

ex5
```py
#ex5

given_list=[1,2,3,2,2,3,1,4,2,5,2,3,3]
count_list=[]
Tlist=[]

for i in range(1,6):
    count_list.append(given_list.count(i))

Tlist.extend(count_list)
count_list.sort()

print("%d가 %d번 등장했습니다." %(Tlist.index(count_list[-1])+1, count_list[-1]))
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/077d028f-3057-4d47-ac84-f578941deaba)

