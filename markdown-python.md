###Day 1 파이썬 변수를 사용한 데이터 관리

##### 6. [대화형 코딩 연습] 출력
```py
print ("Day 1 - Pythin Print Function")
print ("The function is declared like this:")
print ("print('what to print')")
```
___
##### 7. 문자열 처리와 지능형 코드
```py
print ("Hello world!\nHello world!\nHello world!")

print ("Hello" + " " + "Jerry")
```
___
##### 8. [대화형 코등 연습] 디버깅 실습
> Fix the code below 👇
```py
print("Day 1 - String Manipulation")
print('String Concatenation is done with the " + "sign.')
print('e.g. print("Hello " + "world")')
print("New lines can be created with a backslash and n.")
```
___
##### 9. 파이썬의 입력 함수
```py
print ("Hello " + input ("What is your name?"))
```
___
###### 10. [대화형 코딩 연습] 입력 함수
>문제1. input 에 입력한 글자 수 만큼 숫자로 표기되게 하시오.
```py
print (input ("What is your name?”))
```
___
##### 11. 파이썬 변수
```py
name = "Jack"
print (name)

name = "Jerry"
print (name)

name = input("What is your name?¡ ") #name 변수에 input 입력
length = len(name)   #length 변수에 len 함수(글자 수 분석)**

print (length)
```
___
##### 12. [대화형 코딩 연습] 변수
```py
# 문제 2. 중간열에 문자를 추가하여 a와 b값의 결과 값을 반대로 만들어라.
# A 값 100, B 값 200 입력 시 A값 200, B 값 100로 결과 나오게 할 것.
# 적혀있는 코드는 수정 할 수 없음.

a = input("a: ")
b = input("b: ")
#Write your code below this line 👇`

#Write your code above this line 👆`

#🚨 Don't change the code below 👇`
print("a = " + a)
print("b = " + b)
```
###**정답**
```py
c = a
a = b
b = c
```
___
### 13. 변수 이름 짓기
문제 1. 올바른 파이썬 코드는 무엇일까요?
1. var a = 12 
2. a = 12
3. a : 12
4. 12 = a

문제 2. 플레이어 1의 사용자 이름으르 가장 적절한 변수명은 무엇일까요?
1. p1 user name = “jackbauer”
2. 1_player_username = “jackbauer”
3. player1+username = “jackbauer”
4. p1u = “jackbauer”

문제 3. 오류가 발생하는 코드는 어디일까요? 추가 점수를 획득하려면 발생하게 될 오류의 유형도 말씀해주세요.

1. time_until_midnight = "5"
print ("There are" + time_until_Midnight + " hours until midnight")
2. input = "5"
print ("There are" + input + "hours until midnighr")
3. time_until_midnight = "5"
print ("There are" + time_until_midnight + "hours until midnigt")

###**정답**
- 1번 2
- 2번 3
- 3번 1
___
### 14. 밴드명 생성기
```py
#조건 1. 프로그램 인사말을 작성합니다.

#조건 2. 사용자에게 자신이 자란 도시 물어보기.

#조건 3. 사용자에게 애완동물의 이름 물어보기.

#조건 4. 사용자가 입력하 도시명과 애완동물을 합친 밴드 이름 보여주기.

#조건 5. 입력된 커서가 새 줄에 표시되는지 확인
```
### 정답
```py
#1.
print ("밴드이름 만들기에 오신 것을 환영합니다.")
#2.
도시 = input("당신이 사는 도시 이름을 입력하세요.")
#3.
동물 = input("당신이 키우는 애완동물 이름을 입력하세요.")
#4. 
print (도시 + 동물)
#5.
```
___
### 17. 파이썬의 기본 데이터 형식
#### 데이터 타입 종류

###### 1. String "문자형"
- print ("Hello"[4])
- print ("123"+"456")

###### 2. Integer "정수형"
- print (1_234+456)

###### 3. Float (소수형)
- 3.14159

###### 4. Boolean
- True
- False

#### 문제 1.
>잘못된 설명은 무엇일까요?
1. 923 은 Integer 이다
2. “False” 는 Boolean 이다.
3. 853.25 는 Float 다.
4. “523” 은 String 이다.

#### 문제2. 
> 변수 mystery의 데이터 형식은 무엇일까요?

**mystery = 734_529.678**

1. 정수 
2. 문자열
3. Qurtle
4. 실수

##### 문제3. 다음에 출력하게 될 코드 값은 무엇일까요?
>street_name = “Abbey Road”
> print (street_name[4] + street_name[7])

1. eR
2. en
3. yo
4. “Abbey Road”
