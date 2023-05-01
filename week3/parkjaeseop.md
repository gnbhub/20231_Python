```py
#Example1-1

dan = int(input("1~9까지의 숫자를 입력하세요. : "))

if 1<= dan <= 9 :
    for i in range(1,10) :
        print("%2d X %2d = %2d" %(dan, i, dan*i))

else :
    print("1에서 9까지의 수를 다시 입력하세요:")
```
![image](https://user-images.githubusercontent.com/114458636/235449269-6987673e-885e-4397-b02d-665a58c94d13.png)
![image](https://user-images.githubusercontent.com/114458636/235449306-c93cf6b9-e272-4362-aa80-da6a36dbf09b.png)

```py
#Example1-2
list = [1,2,3,4,5,6,7,8,9]
dan = int(input("1~9까지의 숫자를 입력하세요. : "))
i=1;

if dan in list :
    while i<=9 :
        print("%2d X %2d = %2d" %(dan,i,dan*i))
        i += 1

else :
    print("1에서 9까지의 수를 다시 입력하세요:")
```
![image](https://user-images.githubusercontent.com/114458636/235449918-6d7a850c-29df-452f-b9b5-f070e57195b9.png)
![image](https://user-images.githubusercontent.com/114458636/235449944-7458924e-7632-43f2-9aee-d5f9a124e9a5.png)

```py
#Example 2

total = 0;
i=1;

while total<=1000:
    if i%3!=0 and i%5!=0 :
        total = total + i
        i += 1

    else :
        i += 1

print("%d" %total)
```
![image](https://user-images.githubusercontent.com/114458636/235451112-c6190845-dd57-4085-b6a5-f14c7aecc893.png)

```py
#Example 3

year = int(input("검사할 년도를 입력하세요 :"))

if (year%4 == 0 and year%100!=0) or year%400==0 :
    print("윤년입니다.")

else :
    print("윤년이 아닙니다.")
```
![image](https://user-images.githubusercontent.com/114458636/235452105-35ad4716-279f-4562-8fd9-04ef9fd77d32.png)
![image](https://user-images.githubusercontent.com/114458636/235452142-7d3ffdf7-e07b-45ea-8d17-56d755def9ab.png)

```py
#Example 4

i=100

while i <1000 :
    a = i//100
    b = (i%100)//10
    c = i%10

    if a**3 + b**3 + c**3 == i :
        print("%d" %i , end=" ")

    i += 1
```    
![image](https://user-images.githubusercontent.com/114458636/235453397-8be48876-1ec2-4b55-8889-bce5e9f360ff.png)

```py
#Example 5

num = int(input("소수를 판별할 수를 입력하세요 : "))
Trig = 0

for i in range(2,num) :
    if num % i != 0 :
        print("성공")
        continue

    else :
        print("%d는 소수가 아닙니다." %num)
        Trig = 1
        break

if Trig == 0 :
    print("%d는 소수입니다." %num)
```
