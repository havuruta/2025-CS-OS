# 06-1 RAM의 특징과 종류

## 📌 학습 목표
- 해당 챕터의 개념 정리

## ❓ 확인 문제
### Q1. 긴생머리의 KHM군은 술을 마실때 마다 기억을 잃어서 고민중이다.
### 그래서 KHM군은 자신의 기억을 RAM에 담아서 기억이 계속 소실되지 않게 하고 싶다. 어떤 RAM을 사용해야 할까? 


<details>
<summary>정답</summary>

- **SRAM **   

**[해설]**


# 🧠 RAM (Random Access Memory) 이란?  
RAM(램)은 **컴퓨터의 작업 공간** 역할을 하는 메모리입니다.  
- CPU가 프로그램을 실행할 때 **필요한 데이터를 임시로 저장**하는 곳  
- 속도가 빠르지만 **전원이 꺼지면 데이터가 사라지는** **휘발성(Volatile) 메모리**  
- 용량이 크면 클수록 **더 많은 프로그램을 동시에 실행**할 수 있음  

💡 쉽게 말해, RAM은 **책상** 같은 존재!  
- 책상이 클수록 더 많은 책(프로그램)을 펼쳐놓고 작업 가능  
- 하지만 책상 위 자료는 정리하지 않으면 사라지는 것처럼, RAM의 데이터도 **컴퓨터를 끄면 사라짐**

## 램의 종류로 DRAM,SRAM,SDRAM등이 있습니다.

## ✅ 차이점과 장단점  

| 메모리 종류 | 특징 | 장점 | 단점 |
|------------|------------|------------|------------|
| **DRAM (Dynamic RAM)** | 주기적으로 데이터를 새로고침(refresh)해야 하는 메모리 | 가격이 저렴하고, 용량이 크다 | 속도가 상대적으로 느리고, 전력 소비가 많다 |
| **SRAM (Static RAM)** | 새로고침 없이 데이터를 유지하는 메모리 | 속도가 빠르고, 전력 소비가 적다 | 가격이 비싸고, 용량이 작다 |
| **SDRAM (Synchronous DRAM)** | CPU 클럭(Clock)과 동기화된 DRAM | 기존 DRAM보다 속도가 빠르며, 대량의 데이터를 처리하기 좋다 | SRAM보다는 느리고, 여전히 주기적인 새로고침이 필요함 |

---

## 🎯 정리하면?  
- **빠른 속도 원하면?** → **SRAM**  
- **대용량 & 가성비 원하면?** → **DRAM / SDRAM**  
- **CPU랑 동기화해서 더 빠르게 쓰고 싶다?** → **SDRAM**  

💡 그래서 컴퓨터에서는 주로 **SDRAM**(DDR4, DDR5 같은 램)이나 **DRAM**을 사용하고, CPU 내부 캐시는 **SRAM**을 쓴다.

---

</details>

### Q2. DRAM과 SRAM 중 작업 속도가 더 빠르고 시간이 지남에 따라 저장된 내용이 소실되지 않는 메모리는 SRAM이다. 하지만, 컴퓨터 주기억장치에는 DRAM을 사용한다. 그 이유는 무엇인가?

<details>
<summary>정답</summary>

#### SRAM은 DRAM에 비해 속도가 빠르나, 집적도가 낮고 소비 전력도 크며 가격이 더 비싸기 때문에 비교적 저렴한 가격에 큰 용량을 사용 가능한 DRAM을 주기억장치로 사용한다.

- SRAM은 대용량이 필요하지 않고 빠른 처리 속도가 필요한 캐시 메모리에 사용됩니다.

---

</details>

### Q3. RAM의 종류는 크게 네가지가 있다. 네가지의 RAM을 쓰시오.

<details>
<summary>정답</summary>

#### DRAM, SRAM, SDRAM, DDR SDRAM





</details>


### Q4. RAM의 특징과 종류에 대한 설명으로 틀린 것은?

1️. DRAM은 일정 시간마다 데이터를 새로 고쳐야 하는 특성이 있다.

2️. SRAM은 DRAM보다 속도가 빠르고 전력 소비가 적지만, 가격이 비싸다.

3️. RAM은 전원이 꺼져도 데이터를 유지할 수 있는 비휘발성 메모리이다.

4. RAM은 CPU가 직접 접근하여 데이터를 읽고 쓸 수 있는 주기억장치이다.

<details>
<summary>정답</summary>

 **3. RAM은 전원이 꺼져도 데이터를 유지할 수 있는 비휘발성 메모리이다. X**   
  - RAM은 휘발성(Volatile) 메모리이므로, 전원이 꺼지면 저장된 데이터가 모두 사라집니다.
  - CPU가 직접 접근하여 데이터를 읽고 쓸 수 있는 주기억장치

**[해설]**

 **1. DRAM은 일정 시간마다 데이터를 새로 고쳐야 하는 특성이 있다.**   
  - 데이터를 유지하려면 주기적으로 새로 고쳐야(Refresh) 하는 특성이 있음
  - 속도가 빠르고 용량이 크지만 전력 소비가 많음
  

 **2️. SRAM은 DRAM보다 속도가 빠르고 전력 소비가 적지만, 가격이 비싸다.**   
  - 데이터 새로 고침 없이 유지 가능
  - DRAM보다 속도가 빠르고 소비 전력이 낮지만, 가격이 비쌈
  - 주로 CPU 캐시 메모리로 사용됨
  

 **4.  RAM은 CPU가 직접 접근하여 데이터를 읽고 쓸 수 있는 주기억장치이다.** 
  - CPU가 실행 중인 프로그램과 데이터를 저장하는 공간
  - 속도가 빠르며, CPU가 직접 접근하여 연산 수행
  
---

</details>

### Q5. DDR4 SDRAM의 클럭 주파수가 2400MHz일 때, 데이터 전송 속도를 계산하시오.

<details>
<summary>정답</summary>

 **38,400MB/s(=38.4GB/s)**

**[해설]**

**DDR SDRAM 데이터 전송 속도 = 클럭 주파수 * 2 * 8(바이트)**

#### DDR SDRAM은 한 클럭에 두 번씩 CPU와 데이터를 주고 받을 수 있으므로 2를 곱해주며, 단위를 맞춰주기 위해 8을 곱해줌(바이트 표시)

**2400 * 2 * 8 = 38,400MB/s = 38.4GB/s**
  
---

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
