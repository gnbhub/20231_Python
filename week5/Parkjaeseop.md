ex1
```py
#ex1

MyList = []

for i in range(0,5) :
    MyList.append(int(input("숫자를 입력해 주세요. : ")))

MyList.sort()

print("최솟값은 %d입니다." %(MyList[0]))
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/51905752-d55c-4677-a6f3-dc6d857ce038)

ex2
```py
#ex2

MyList = []

for i in range(0,5) :
    MyList.append(int(input("숫자를 입력해 주세요. : ")))

MyList.sort()

print("최댓값은 %d입니다." %(MyList[-1]))
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/c4c79cd8-9d9a-434d-982a-8be4f5d76465)

ex3
```py
#ex3

Stu1=[]
Stu2=[]
Stu3=[]

for i in range(0,3) :
    Stu1.append(int(input("점수 입력 : ")))

for i in range(0,3) :
    Stu2.append(int(input("점수 입력 : ")))

for i in range(0,3) :
    Stu3.append(int(input("점수 입력 : ")))

print("학생1의 총점수 : %d" %(Stu1[0]+Stu1[1]+Stu1[2]))
print("학생2의 총점수 : %d" %(Stu2[0]+Stu2[1]+Stu2[2]))
print("학생3의 총점수 : %d" %(Stu3[0]+Stu3[1]+Stu3[2]))
```
![image](https://github.com/gnbhub/20231_Python_Study/assets/114458636/85d03576-939c-4178-ae47-9f6ce9bf731a)

