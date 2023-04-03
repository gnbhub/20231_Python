Ex 1

```py
numinput = input("세자리 수를 입력하세요. ---> ")

print("백의 자리수는 '%c', 십의 자리수는 '%c', 일의 자리수는 '%c'입니다." %(numinput[0], numinput[1], numinput[2]))

```
![image](https://user-images.githubusercontent.com/114458636/229507883-b0142a3f-3bcd-407d-a6dd-4f3bb94b6804.png)

Ex 2

```py
name = input("사용자의 이름이 어떻게 되나요? ---> ")
age = int(input("사용자의 나이가 어떻게 되나요? ---> "))

print("'%s님의 10년 후 나이는 %d살 입니다.'" %(name, age+10))
```
![image](https://user-images.githubusercontent.com/114458636/229509153-68e1f258-e37a-4516-8df9-31dfef39c7ed.png)

Ex 3

```py
Numlist = input("8자리 수를 입력하시오. ---> ")

print("\'거꾸로 출력한 결과는 ", end='')

for i in range(0,8) :
    print("%c" %(Numlist[7-i]), end='')

print("입니다.\'")
```
![image](https://user-images.githubusercontent.com/114458636/229510414-73b71f26-fbeb-4b9f-b45f-e4adb4969ab1.png)
