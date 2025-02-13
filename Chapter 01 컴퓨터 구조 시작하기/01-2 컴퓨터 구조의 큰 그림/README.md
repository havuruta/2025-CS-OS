# 01-2 컴퓨터 구조의 큰 그림

## 📌 학습 목표
- 해당 챕터의 개념 정리

## ❓ 확인 문제

### Q1. 다음 중 CPU의 구성 요소에 해당하지 않는 것을 고르세요.

#### 1️⃣ 제어 장치  2️⃣ 시스템 버스 3️⃣ 레지스터 4️⃣ ALU

<details>
<summary>정답</summary>

#### 2️⃣ 시스템 버스 : 메인 보드에 연결된 컴퓨터의 네가지 핵심 부품들이 정보를 교환하는 통로를 말합니다. 

**CPU 구성 요소 세가지**
#### 1️⃣ 제어 장치 : 제어 신호를 보내고 명령어를 해석하는 장치입니다.
#### 3️⃣ 레지스터 : 프로그램 실행에 관련된 값들을 임시적으로 저장하는 역할을 하는 작은 임시 저장 장치입니다.
#### 4️⃣ ALU : CPU 내에서 계산을 담당하는 부분입니다. 산술논리연산장치 라고도 합니다.

</details>

### Q2. 주기억장치와 보조기억장치의 차이점을 설명해보세요.

<details>
<summary>정답</summary>

#### 주기억장치 : RAM(메모리 라고도 함), ROM이 이에 해당합니다. 현재 실행되고 있는 프로그램의 명령어나 데이터를 주소값에 정돈하여 저장하는 역할을 합니다. 단, 컴퓨터가 종료될 시 저장 내용이 사라집니다.

#### 보조기억장치 : HDD, SSD, USB, CD 등이 해당합니다. 주기억장치보다 저장 용량이 크고, 컴퓨터가 종료되어도 저장한 내용이 사라지지 않습니다. 그렇기에, 보관하고 싶은 프로그램 정보들이 저장됩니다.

</details>

### Q3. CPU에서 "메모리 읽기"라는 신호를 보낼 때 이용하는 시스템 버스는 무엇일까요?

<details>
<summary>정답</summary>

#### 제어 버스 : 제어 신호를 주고받는 통로이며, "메모리 읽기"는 제어 신호에 해당하기 때문.

</details>

### Q4. 주기억장치의 RAM과 ROM의 차이

<details>
<summary>정답</summary>

**RAM(Random Acess Memory)** 은 말 그대로 랜덤 엑세스 메모리다. 우리가 아는 램수면의 램은 아니다.( >_* ) 메인메모리에 주로 사용되며 전원을 켜고 있을 떄는 데이터를 사용 가능하지만, 전원이 꺼지면 데이터가 사라지는 휘발성 메모리다.

**ROM(Read Only Memory)** 는 한번 저장한 테이터를 빠른 속도로 읽어낼 수 있다는 장점이 있지만, 다시 기록은 불가능 하기 때문에 현대에 들어서서는 사용 범위가 많이 줄어들었다.
그럼에도 한번 기록된게 변경 불가능 하다는 특성을 이용 할 때는 매우 유용하다.

</details>

### Q5. 버스(Bus)란?

<details>
<summary>정답</summary>

**버스(Bus)**의 어원은 "버스"라는 단어가 라틴어의 "omnibus(모두를 위한)"에서 유래했다는 점에 있다. "Omnibus"는 '모두를 위한', 즉 '여러 사람을 동시에 수송하는' 뜻을 가지고 있다다. 이 단어에서 버스라는 용어가 발전해, 데이터를 여러 장치들이 동시에 공유할 수 있는 통로로서의 개념으로 사용되기 시작했다.

컴퓨터 하드웨어는 크게 **중앙처리장치(CPU)** , **메인 메모리(기억 장치)** , **입출력 장치**로 나뉘며 이들은 모두 버스(Bus)로 연결되어 있다. **버스(Bus)** 란 CPU, 주기억 장치, 외부의 입출력 장치 사이의 정보 전송을 위한 전기적 통로이다.  즉, 컴퓨터의 많은 장치들이 서로 데이터를 주고 받기 위한 통로이며 버스의 크기, 버스를 통한 데이터 전송 속도가 시스템의 성능을 좌우한다.

</details>



### Q6. 다음 중 시스템 버스가 아닌 것은 ?
#### 1️⃣ 제어버스  2️⃣ 주소버스 3️⃣ 메모리버스 4️⃣ 데이터버스

<details>
<summary>정답</summary>

#### 3️⃣ 메모리버스 

</details>


### Q7. 보조기억장치는 메모리라고 할 수 있다. (O / X)

<details>
<summary>정답</summary>

#### X
주기억장치는 실행되는 프로그램의 명령어와 데이터를 저장하지만, 전원이 꺼지면 저장된 내용을 잃는다. 주기억장치는 메모리라고도 한다.

</details>


### Q8. CPU가 메모리에 어떤 값을 저장하고 싶을 때는 메모리를 향해 메모리 읽기 라는 신호를 보낸다. (O / X)

<details>
<summary>정답</summary>

#### X
CPU가 메모리에 저장된 값을 읽고 싶을 때는 메모리를 향해 메모리 읽기라는 제어신호를 보낸다.
CPU가 메모리에 어떤 값을 저장하고 싶을 때는 메모리를 향해 메모리 쓰기 라는 신호를 보낸다.

</details>


### Q9. 다음 중 CPU에 관한 설명으로 옳지 않은 것을 고르세요.  

#### 1️⃣ CPU 내부에는 ALU, 레지스터, 제어장치가 있다.
#### 2️⃣ CPU가 메모리에 저장된 값을 읽고 싶을 땐 메모리 쓰기라는 제어 신호를, 저장하고 싶을 땐 메모리 저장이라는 제어 신호를 보낸다.  
#### 3️⃣ CPU는 메모리에 저장된 값을 읽어 들이고, 해석하고, 실행하는 장치이다. 
#### 4️⃣ ALU는 계산하는 장치, 레지스터는 임시 저장 장치, 제어장치는 제어 신호를 발생시키고 명령어를 해석하는 장치이다.

<details>  
<summary>정답</summary>  

#### 2️⃣ CPU가 메모리에 저장된 값을 읽고 싶을 땐 메모리 쓰기라는 제어 신호를, 저장하고 싶을 땐 메모리 저장이라는 제어 신호를 보낸다. 
- 메모리에 저장된 값을 읽을 때는 **메모리 읽기** 라는 제어 신호를 보냅니다.
- 메모리에 값을 저장할 때는 **메모리 쓰기** 라는 제어 신호를 보냅니다.
---

#### 1️⃣ CPU 내부에는 ALU, 레지스터, 제어장치가 있다.
- CPU는 크게 세가지로 나누어진다.  
  1. **ALU**  
     덧셈, 뺄셈, 곱셈 등의 연산 및 논리 연산(AND, OR, NOT 등)을 수행합니다.  
  2. **레지스터**  
     명령어 실행을 위한 임시 데이터(데이터, 주소, 상태 정보 등)을 저장합니다.  
  3. **제어장치(Control Unit)**  
     명령어를 해석하고 실행 순서를 제어하는 역할을 합니다. 

#### 2️⃣ 현재 실행되는 프로그램의 데이터와 명령어를 저장하는 역할을 한다. 
- RAM은 프로그램 실행 중 CPU가 빠르게 접근할 수 있도록 **명령어와 데이터**를 저장하는 공간입니다.

#### 4️⃣ 프로그램을 실행하기 위해서는 명령어와 데이터가 메모리에 저장되어 있어야 한다.  
- **CPU**가 프로그램을 실행하려면 해당 프로그램의 **명령어와 데이터**가 반드시 메모리에 있어야 합니다. 
- 하지만, **OS** 는 필요한 부분만 **메모리** 에 올리고, 나머지는 **보조기억장치** 에서 불러옵니다. 

</details>

### Q10. 다음 중 메모리에 관한 설명으로 옳지 않은 것을 고르세요.  

#### 1️⃣ 메모리에 저장된 위치는 주소를 통해 접근할 수 있다.  
#### 2️⃣ 현재 실행되는 프로그램의 데이터와 명령어를 저장하는 역할을 한다.  
#### 3️⃣ 컴퓨터가 종료되어도 메모리에 저장된 데이터는 유지된다. 
#### 4️⃣ 프로그램을 실행하기 위해서는 명령어와 데이터가 메모리에 저장되어 있어야 한다.

<details>  
<summary>정답</summary>  

#### 3️⃣ 컴퓨터가 종료되어도 메모리에 저장된 데이터는 유지된다.
- 데이터를 유지하는 역할은 **보조기억장치** 가 담당합니다.
- **RAM**은 휘발성 메모리로, 전원이 꺼지면 데이터가 사라집니다. 
- **ROM**은 비휘발성 메모리로, 전원이 꺼져도 저장된 데이터가 유지됩니다. 

---

#### 1️⃣ 메모리에 저장된 위치는 주소를 통해 접근할 수 있다.  
- 메모리는 각 데이터가 저장된 위치를 **"주소"라는 고유한 값**으로 관리합니다.

#### 2️⃣ 현재 실행되는 프로그램의 데이터와 명령어를 저장하는 역할을 한다. 
- RAM은 프로그램 실행 중 CPU가 빠르게 접근할 수 있도록 **명령어와 데이터**를 저장하는 공간입니다.

#### 4️⃣ 프로그램을 실행하기 위해서는 명령어와 데이터가 메모리에 저장되어 있어야 한다.  
- **CPU**가 프로그램을 실행하려면 해당 프로그램의 **명령어와 데이터**가 반드시 메모리에 있어야 합니다. 
- 하지만, **OS** 는 필요한 부분만 **메모리** 에 올리고, 나머지는 **보조기억장치** 에서 불러옵니다. 

</details>

### Q11. 다음 중 보조기억장치와 입출력장치에 대한 설명으로 옳지 않은 것은?

#### 1️⃣ 보조기억장치에 저장된 데이터는 컴퓨터가 종료되어도 삭제되지 않는다.
#### 2️⃣ 입출력장치에는 마이크, 스피커, 마우스 등이 해당된다.
#### 3️⃣ 보조기억장치는 입출력장치의 일종으로 볼 수 없다.
#### 4️⃣ 보조기억장치와 입출력장치를 통틀어 주변장치라 말할 수 있다.

<details>
<summary>정답</summary>

#### 3️⃣ 보조기억장치는 입출력장치의 일종으로 볼 수 없다.
- 보조기억장치는 메모리를 보조하는 기능을 수행하는 입출력장치의 일종으로 볼 수 있습니다.
- 보조기억장치와 입출력장치를 주변장치라 통칭하기도 합니다.

---

</details>

### Q12. 시스템 버스에는 주소 버스, 데이터 버스, 제어 버스가 존재한다. 다음 중 각 버스에서 주고받을 수 있는 정보로 가장 알맞은 것은?

#### 1️⃣ 주소 버스 - 읽고자 하는 메모리 주소 / 데이터 버스 - 메모리 읽기 신호 / 제어 버스 - 메모리 쓰기 신호
#### 2️⃣ 주소 버스 - 메모리 읽기 신호 / 데이터 버스 - 저장할 데이터 / 제어 버스 - 메모리 쓰기 신호
#### 3️⃣ 주소 버스 - 메모리 쓰기 신호 / 데이터 버스 - 읽고자 하는 주소 / 제어 버스 - 저장할 데이터
#### 4️⃣ 주소 버스 - 저장할 메모리 주소 / 데이터 버스 - 저장할 데이터 / 제어 버스 - 메모리 쓰기 신호

<details>
<summary>정답</summary>

#### 4️⃣ 주소 버스 - 저장할 주소 / 데이터 버스 - 저장할 데이터 / 제어 버스 - 메모리 쓰기 신호
- 시스템 버스는 주소 버스, 데이터 버스, 제어 버스로 구성되어 있습니다.
- 주소 버스는 주소를, 데이터 버스는 명령어와 데이터를, 제어 버스는 제어 신호를 주고받습니다.

- 문제 상황에서 각 버스에서 주고받을 수 있는 정보는 다음과 같습니다.
   - 메모리 속 명령어를 읽어 들이기 : 주소 버스 - 읽고자 하는 메모리 주소 / 제어 버스 - 메모리 읽기 신호
   - 메모리에 데이터 저장하기 : 주소 버스 - 저장할 메모리 주소 / 데이터 버스 - 저장할 데이터 / 제어 버스 - 메모리 쓰기 신호

---

</details>

### Q13. 컴퓨터의 4가지 핵심 부품에는 CPU, 주기억장치, 보조기억장치, 입출력장치가 존재한다. 다음 중 각 부품에 해당하는 장치들로 가장 알맞은 것은?
#### 1️⃣ CPU - 레지스터, 주기억장치 - USB, 보조기억장치 - SSD, 입출력장치 - ALU
#### 2️⃣ CPU - ALU, 주기억장치 - ROM, 보조기억장치 - RAM, 입출력장치 - 마우스
#### 3️⃣ CPU - 제어장치, 주기억장치 - RAM, 보조기억장치 - 하드디스크, 입출력장치 - 키보드
#### 4️⃣ CPU - 레지스터, 주기억장치 - ROM, 보조기억장치 - ALU, 입출력장치 - 프린터

<details>
<summary>정답</summary>

#### 3️⃣ CPU - 제어장치, 주기억장치 - RAM, 보조기억장치 - 하드디스크, 입출력장치 - 키보드

- 문제에서 각 핵심 부품에 해당하는 장치들은 다음과 같습니다.
   - CPU - ALU, 제어장치, 레지스터
   - 주기억장치 - RAM, ROM
   - 보조기억장치 - 하드디스크, SSD, USB
   - 입출력장치 - 마우스, 키보드, 프린터

---

</details>

### Q14. CPU가 메모리에서 데이터를 읽어오는 단계에서 각 단계 사용하는 시스템 버스를 적으세요.
#### 1️⃣ "메모리 읽기" 제어 신호 내보냄
#### 2️⃣ 읽고자하는 주소 내보냄
#### 3️⃣ 메모리 CPU가 요청한 주소에 있는 내용 보냄

<details>
<summary>정답</summary>

#### 1️⃣ : 제어버스, 2️⃣ : 주소버스, 3️⃣ : 데이터버스
  
</details>

### Q15. 컴퓨터 4가지 핵심 부품이 아닌 것은?
#### 1️⃣ 중앙처리장치(CPU)
#### 2️⃣ 레지스터
#### 3️⃣ 보조기억장치
#### 4️⃣ 입출력장치

<details>
<summary>정답</summary>

#### 2️⃣ 레지스터 : 데이터 임시 저장 장치
- CPU 내부에서 연산이나 제어를 수행하는 데 필요한 데이터를 빠르게 읽고 쓸 수 있도록 도와줌
  
</details>

### Q16. 입출력 장치의 예시로 알맞지 않은 것은?
#### 1️⃣ 마우스
#### 2️⃣ 키보드
#### 3️⃣ 프린터
#### 4️⃣ SSD

<details>
<summary>정답</summary>

#### 4️⃣ SSD : 보조기억장치
- SSD는 HDD보다 빠른 속도로 데이터를 읽고 쓸 수 있고 충격에 강한 것이 장점
  
</details>

## 📝 사용법  
### 이렇게 활용해 보세요! ✨  
1. ❓ 확인 문제 아래에 본인이 만든 질문을 추가하세요.  
2. 설명이 길어질 경우, 따로 마크다운 파일을 만들고 링크를 함께 추가해 주세요! 🔗  

### 🔗 링크 추가 방법  
1. 먼저 질문을 작성합니다.  
2. 링크를 적용할 문장을 마우스로 선택합니다.  
3. URL을 붙여넣습니다.  
4. 마크다운 형식으로 `[내용](링크)` 형태로 정리됩니다.  
