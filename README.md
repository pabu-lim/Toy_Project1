## 토이 프로젝트1 JAVA


여행 여정을 기록과 관리하는 SNS 서비스 1단계


### 🕰️ 개발 기간

---

- 23.09.04일 - 23.09.08일

### 🧑‍🤝‍🧑 멤버 구성

---

- [권민우](https://github.com/Kwonminwoo)

- [권도형](https://github.com/tfedohk)

- [백인권](https://github.com/BackInGone)

- [임경민](https://github.com/pabu-lim)

- [유현](https://github.com/yuhyun1)

### ⚙️ 개발 환경

---

- Java 11
- Gradle
- 의존성
    - opencsv 5.7.1
    - jackson-databind 2.15.2


### 📌 주요 기능

---

#### - 여행 기록 및 여정 기록 기능
- 여행 일정 기록
- 하나의 여행에 여러 개의 일정 기록


#### - 여행 정보 조회 기능
- 저장된 여행 전체 리스트 조회
- 여행 전체 리스트에서 확인된 아이디를 입력하면 해당 여행 정보 조회
- JSON파일과 CSV파일 각각 조회

### 💡 착안사항

---

#### - MVC
- 컨트롤러
- 모델
- 뷰
- 서비스

#### - 예외처리
- 여행 정보가 없거나(파일입출력), 여정이 포함되어 있지 않다면 오류 메시지 출력
- 입력값이 가능한 범주에 없거나, 타입에 맞지 않으면 오류 메시지 출력
- JSON, CSV 파일 형식에 맞지 않다면 오류 메시지 출력
- 한글 문자가 깨지지 않게 처리

#### - 리팩토링
- 상수 패키지(constant) 분리
- 예외처리 패키지(exception) 분리
- DAO 패턴 사용(TripDao Class) : 서비스 로직과 데이터엑세스 로직을 분리하여 재사용성, 유연성 보장
- 유틸 패키지(util) 분리

### 🛠️ 클래스 다이어그램

---

![img.png](img.png)


### 🛠️ 시퀀스 다이어그램

---

- 추가 예정

### 💻 각 메뉴 화면

---

- 개발이 끝난 후 캡쳐 화면 추가 예정
