# 02-1 0과 1로 숫자를 표현하는 방법

## 📌 학습 목표

- 해당 챕터의 개념 정리

## ❓ 확인 문제

### Q1. 다음 중 십진수 숫자 10을 이진수로 가장 올바르게 표현한 것은?

#### 1️⃣ 10<sub>(2)</sub>

#### 2️⃣ 1010<sub>(2)</sub>

#### 3️⃣ 0x1010

#### 4️⃣ 1010<sub>(16)</sub>

<details>
<summary>정답</summary>

#### 2️⃣ 1010<sub>(2)</sub>

- 이진수와 십진수 간 표현의 혼동을 예방하기 위해, 이진수 끝에 아래첨자 <sub>(2)</sub> 를 붙이거나 이진수 앞에 0b를 붙입니다.

- 따라서 십진수 숫자 10을 이진수 1010으로 변경한 뒤, 1010<sub>(2)</sub> 혹은 0b1010으로 표기하는 것이 가장 올바르다 할 수 있습니다.

- 각 수를 십진수로 표현하면 다음과 같습니다.


  - 10<sub>(2)</sub> -> 2
  - 1010<sub>(2)</sub> -> 10
  - 0x1010 -> 4112
  - 1010<sub>(16)</sub> -> 4112

    - 10<sub>(2)</sub> -> 2
    - 1010<sub>(2)</sub> -> 10
    - 0x1010 -> 4112
    - 1010<sub>(16)</sub> -> 4112


---

</details>


### Q2. 왜 컴퓨터는 2진수와 16진수로 사용할까요

<details>
<summary>정답</summary>


### 데이터의 오류를 최소화하고 비용과 시간을 효율적으로 처리하기 위해서

#### 2진수

- 전기의 **ON/OFF**로 정보를 담을 수 있기 때문에(10진수로 표현할 경우 0V~9V까지 세기조절을 해야해서 정보의 정확성을 해칠 수 있음)
- 10진수같은 다른 진법을 쓰면 회로의 갯수가 늘어나서 **비효율적**. **2진법**은 ON/OFF를 수행할 비트만 있으면 가능
- 컴퓨터 내부에 트랜지스터가 수십억개가 들어가 있는데 **트랜지스터**가 **스위치 역할**을 수행할 수 있음

---

#### 16진수



### 데이터의 오류를 최소화하고 비용과 시간을 효율적으로 처리하기 위해서

#### 2진수
- 전기의 **ON/OFF**로 정보를 담을 수 있기 때문에(10진수로 표현할 경우 0V~9V까지 세기조절을 해야해서 정보의 정확성을 해칠 수 있음)
- 10진수같은 다른 진법을 쓰면 회로의 갯수가 늘어나서 **비효율적**. **2진법**은 ON/OFF를 수행할 비트만 있으면 가능
- 컴퓨터 내부에 트랜지스터가 수십억개가 들어가 있는데 **트랜지스터**가 **스위치 역할**을 수행할 수 있음
---
#### 16진수

- 2진수로만 표한하면 길이가 너무 길어지기 때문
- 2진수에서 16진수로의 변환이 10진수로 변환하는 것 보다 쉽기때문
- 정보 표현은 16진수로 하지만 내부에서는 2진수 형태로 표현함

</details>


### Q3. 1의 보수가 아닌 2의 보수로 음수 만드는 이유?

<details>
<summary>접기/펼치기</summary>

1의 보수는 0은 1로, 1은 0으로 하는 방식이다. 이를 예시를 통해 알아보자.  
10진수로 7인 0111은 1의 보수로 나타내면 1000이다. 그렇다면 0111과 1000이 더해지면 7 + (-7)인 0 즉 0000이 나와야 하지만 1111이 나오므로 1의 보수는 사용할 수 없다.

</details>

### Q4. 1MB는 1024kB이다. ( O/ X )

<details>
<summary>접기/펼치기</summary>


#### X

#### X 


1MB는 1000kB이다. 무슨 말을 하고자 하는지 이해는 가지만 그 단위는 kB가 아닌 KiB로 엄연히 둘은 다른 방식이다.

</details>


### Q5. 8진수와 16진수

<details>
<summary>접기/펼치기</summary>


#### 8진수

8진수는 $2^3$으로 2진수를 간결하게 표현할 수 있다. 이는 옛날 컴퓨터 시스템에서 자주 사용되었으며 그 예시로는 PDP-8과 같은게 있다. lowlevel 프로그래밍에서, 특히 시스템 프로그래밍이나 하드웨어와 가까운 부분에서는 여전히 유용하다.

#### 16진수

16진수는 $2^4$로 8진수보다 더 큰 단위다. 9 이후에는 A~F사이의 문자를 이용하여 사람들이 이해하기에 쉽게 한다. 요즘의 컴퓨터에서 자주 사용하며 메모리 주소표현, 바이너리 데이터 표현, 네트워크 프로토콜 등 에서 사용된다. 더 나아가 디버깅툴에서 데이터나 코드 메모리 덤프확인 할 때, 웹 개발의 색상에서도 사용된다.

#### 8진수  
8진수는 $2^3$으로  2진수를 간결하게 표현할 수 있다. 이는 옛날 컴퓨터 시스템에서 자주 사용되었으며 그 예시로는 PDP-8과 같은게 있다. lowlevel 프로그래밍에서, 특히 시스템 프로그래밍이나 하드웨어와 가까운 부분에서는 여전히 유용하다.

#### 16진수  
16진수는 $2^4$로 8진수보다 더 큰 단위다. 9 이후에는 A~F사이의 문자를 이용하여 사람들이 이해하기에 쉽게 한다. 요즘의 컴퓨터에서 자주 사용하며 메모리 주소표현, 바이너리 데이터 표현, 네트워크 프로토콜 등 에서 사용된다. 더 나아가 디버깅툴에서 데이터나 코드 메모리 덤프확인 할 때, 웹 개발의 색상에서도 사용된다.  


이처럼 필요에 따라 점점 진수 사용이 발전되어졌다. 혹시나 나중에는 32진수, 더 나아가 64진수를 쓸 날이 올지도 모르겠다.

</details>

### Q6. 다음 중 계산 값이 틀린 것은?

#### 1️⃣ 1MB = 1,000,000byte


#### 2️⃣ 1GiB = 1,048,576KiB

#### 3️⃣ 2GB = 2,048MB

#### 4️⃣ 1MB = 8,000,000bit

<details>  
<summary>정답</summary>

#### 2️⃣ 1GiB = 1,048,576KiB
#### 3️⃣ 2GB = 2,048MB
#### 4️⃣ 1MB = 8,000,000bit

<details>  
<summary>정답</summary>  


#### 3️⃣ 2GB = 2,048MB

**풀이**

##### 1️⃣ 1MB = 1,000KB = 1,000,000byte

##### 2️⃣ 1GiB = 1,024MiB = 1,048,576KiB

##### 3️⃣ 2GB = 2,000MB

- 1024단위를 사용하는 건 GiB(기비바이트)이다.

##### 4️⃣ 1MB = 1,000,000byte = 8,000,000bit

</details>


### Q7. 다음 2진수를 16진수, 10진수로 바꿔보시오.

#### 0001100001011111(2)

<details>  

<summary>정답</summary>

<summary>정답</summary>  


#### 18AF(16), 6319(10)

**풀이**

#### 0001 1000 0101 1111 -> 1 8 A F


#### 18AF(16) -> (16^3 _ 1)+(16^2 _ 8)+(16^1 _ A)+(16^0 _ 15) = 6319(10)

</details>

### Q8. CPU가 한 번에 처리할 수 있 데이터의 크기를 의미하는 것을 \_\_ 라고 합니다.

#### 18AF(16) -> (16^3 * 1)+(16^2 * 8)+(16^1 * A)+(16^0 * 15) = 6319(10) 

</details>

### Q8. CPU가 한 번에 처리할 수 있 데이터의 크기를 의미하는 것을 __ 라고 합니다.


<details>
<summary>정답</summary>

정답: **워드**

CPU가 한 번에 16비트를 처리할 수 있다면 1워드는 16비트, 한 번에 32비트를 처리할 수 있다면 1워드는 32비트입니다.

워드의 절반 크기를 **하프 워드**, 1배 크기를 **풀 워드**, 2배 크기를 **더블 워드**라고 부릅니다.


</details>

### Q9. CPU가 한번에 처리할 수 있는 비트 및 워드가 주어졌을 때 몇 비트인지 계산하시오.

- 처리 비트 : 16bit.

1.  1워드 :
2.  2워드 :
3.  3워드 :

<details>
<summary>정답</summary>
1. 16bit
2. 32bit
3. 48bit

</details>

### Q10. 실제 이진수만 봐서는 음수인지, 양수인지 구분하기 어렵다. 컴퓨터 내부에 이를 구분하기 위해 사용하는 것은?

<details>
<summary>정답</summary>

#### 플래그

</details>


### Q11. -7을 이진수로 표현하면? (2의 보수 사용)

<details>
<summary>정답</summary>

#### 1001

- 2의 보수 : 어떤 수를 그보다 큰 2<sup>n</sup>에서 뺀 값 (1️⃣7의 이진수 : 0111 &rarr; 2️⃣모든 이진수 뒤집기 : 1000 &rarr; 3️⃣1 더하기 : 1001)
- 음수 표현 다른 방법 &rarr; Signed Magnitude 방법 : 보통 가장 왼쪽 첫번째 비트를 부호비트로 사용(ex) -7 &rarr; 1111)

</details>

### Q12. 10진수 숫자 27을 2진수, 8진수, 16진수로 각각 변환하시오.

<details>
<summary>정답</summary>

1. 2진수 : 11011
2. 8진수 : 33
3. 16진수 : 1B

</details>

### Q13. 다음 설명 중 옳지 않은 것을 고르시오.

1. 이진법은 숫자가 1을 넘어가는 시점에 자리 올림을 하여 0과 1만으로 모든 숫자를 표현하는 방법이다.
2. 이진수의 음수를 표기하기 위해서는 2의 보수를 구해 이 값을 음수로 간주한다.
3. 이진법의 코드상 표기 방식으로 숫자 앞에 0x를 붙인다.
4. 이진법의 수학적 표기 방식으로 숫자 뒤에 (2)를 붙인다.

<details>
<summary>정답</summary>

3.  이진법의 코드상 표기 방식으로 숫자 앞에 0x를 붙인다.

해설


- 0x : 십육진법의 코드상 표기 방식
- 0b : 이진법의 코드상 표기 방식

</details>

### Q14. 데이터를 00할 때 십육진법을 자주 사용한다.

<details>
<summary>정답</summary>

#### 표현

- 십육진법은 데이터를 표현할 때 자주 사용한다. 이진수를 통해 컴퓨터가 이해하는 숫자 정보를 직접적으로 표현할 수는 있으나, 숫자의 길이가 너무 길어진다는 단점이 존재한다. 그래서 이진수에 비해 더 적은 자릿수로 더 많은 정보를 표현할 수 있는 십육진법을 사용하는 것이다.

</details>

### Q15. 간혹 코프로그래밍을 할 때 코드에 십육진수를 직접 쓰는 경우도 있다 [O, X]

<details>
<summary>정답</summary>

#### O

- 하드웨어와 밀접하게 맞닿아 있는 개발 분야에서는 코드에 십육진수를 직접 쓰는 경우도 있다.

- 메모리 주소를 다루는 경우 16진수를 표현하면 읽기 쉽기에 사용하는 경우들이 있다.

</details>

### Q16. 이진수의 음수 표현처럼 십진수나 십육진수에서도 음수를 표현하기 위한 보수 표현이 존재한다 [O, X]

<details>
<summary>정답</summary>

#### O

- 십진수의 보수 표현 방식은 9의 보수 방식과 10의 보수 방식을 이용한다. 각 자릿수를 9에서 뺀 값으로 나타내는 9의 보수 방식과 9의 보수에 1을 더하는 10의 보수 방식이 있다.

- 십육진수의 경우 각 자리 숫자를 F(15)에서 뺀 값인 F의 보수와 F의 보수에 1을 더하는 16의 보수를 구하는 두 방식으로 찾을 수 있다.

- 십육진법은 사람이 데이터를 보기 쉽게 만든 '표현'일 뿐이기에 컴퓨터 내부에서 데이터는 이진법으로 변환되어 연산된다!(기본적으로 이진연산을 수행하기에 이진수의 보수를 쓰는 것이 더 효율적이다!)

</details>

### Q17. 인텔의 x86 cpu는 32bit 운영체제를 설치하여 사용할 수 있다는 문장의 의미는 무엇인가?

<details>
<summary>정답</summary>

x86 cpu의 워드는 32bit임으로 word 단위가 32bit인 cpu에서 동작되도록 설계된 운영체제를 설치하여 사용해야 한다는 의미

</details>

### Q18. 십육진수는 종종 코드에 바로 사용되기도 한다. 앞으로 배우게 될 CSS에서도 십육진수를 사용하는데 무엇을 표현하기 위해 사용하는가?

<details>
<summary>정답</summary>

CSS에서는 주로 색상을 표현하기 위해 색상 이름, rgba 값이나 십육진수를 사용한다. 십육진수로 표현할 때는 RR/GG/BB로 나누어 표현한다.

</details>

### Q19. n개의 비트로는 $-2^n$ 과 $2^n$을 동시에 표현할 수 없다. 그 이유는

<details>
<summary>정답</summary>

2^n의 보수로 -2^n을 표현하고자 할 때 2^n의 보수가 자기 자신이 되기 때문에 동시에 표현할 수 없다. 플래그는 n+1개의 비트를 사용하고 하나의 비트를 부호 비트로 활용하는 것이기에 n개로는 안된다.

</details>

### Q20. 컴퓨터에서 데이터를 표현할 때 이진법 외에 십육진법도 자주 사용한다. 이 중에서 십육진법은 주로 어느 곳에서 활용되는가?

<details>
<summary>정답</summary>

- 십육진법은 비트수가 많아 사람이 읽기 불편한 이진법과 다르게 4비트를 한 자리로 표현할 수 있어 가독성이 좋다. 그렇기에 **메모리 주소, 기계어 코드, 디버깅 과정**에서 십육진법 표기가 널리 활용된다. 

</details>

### Q21. 16진수 A5(16)를 이진수로 변환하면?

<details>
<summary>정답</summary>

A(16) = 1010(2)

5(16) = 0101(2)

A5(16) = 1010 0101(2)

</details>

## 📝 사용법

### 이렇게 활용해 보세요! ✨

1. ❓ 확인 문제 아래에 본인이 만든 질문을 추가하세요.
2. 설명이 길어질 경우, 따로 마크다운 파일을 만들고 링크를 함께 추가해 주세요! 🔗

- 0x : 십육진법의 코드상 표기 방식
- 0b : 이진법의 코드상 표기 방식

## 📝 사용법  
### 이렇게 활용해 보세요! ✨  
1. ❓ 확인 문제 아래에 본인이 만든 질문을 추가하세요.  
2. 설명이 길어질 경우, 따로 마크다운 파일을 만들고 링크를 함께 추가해 주세요! 🔗  

### 🔗 링크 추가 방법  
1. 먼저 질문을 작성합니다.  
2. 링크를 적용할 문장을 마우스로 선택합니다.  
3. URL을 붙여넣습니다.  
4. 마크다운 형식으로 `[내용](링크)` 형태로 정리됩니다.  

