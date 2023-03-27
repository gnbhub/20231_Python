week1 Homework

Ex 3

```py
price = int(input("금액 입력 : "))

a = price // 1000 #1000원

min1 = (price-(a*1000)) #중간값

b = min1 // 500 #500원

min1 = min1 - (b*500)

c = min1 // 100 #100원

min1 = min1 - (c*100)

d = min1 // 50

min1 = min1 - (d*50) #50원

e = min1 // 10

f = min1 - (e*10) #1원

print("%d won = %d * 1,000 won + %d * 500 won + %d * 100 won + %d * 50 + %d * 10 won + %d * 1 won, total %d is the minimum" %(price,a,b,c,d,e,f,a+b+c+d+e+f))
```
![image](https://user-images.githubusercontent.com/114458636/227931658-7b55d87f-fc7c-41f6-9b52-adcc685f474b.png)
