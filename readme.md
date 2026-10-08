# 🧮 Streamlit 간단 정수 계산기

Streamlit을 활용하여 두 정수와 연산자를 입력받아 결과를 계산해 주는 Simple Web Application입니다.

---

## 📌 주요 기능

- **한 줄씩 입력 인터페이스**: 첫 번째 정수, 연산자, 두 번째 정수를 순서대로 입력받습니다.
- **연산자 유효성 검사**: `+`, `-`, `*`, `/` 이외의 문자가 입력되면 에러 메시지를 표시합니다.
- **예외 처리**:
  - 정수가 아닌 문자 또는 실수 입력 시 에러 메시지 출력
  - `0`으로 나누기 시도 시 에러 메시지 출력

---

## 🚀 시작하기

### 1. 필수 조건 (Prerequisites)

- Python 3.8 이상

### 2. 패키지 설치

`requirements.txt` 파일에 정의된 패키지를 설치합니다.

```bash
pip install -r requirements.txt
```

### 3. 앱 실행

터미널에서 아래 명령어를 입력하여 Streamlit 애플리케이션을 실행합니다.

```bash
streamlit run app.py
```

명령어를 실행하면 브라우저에 `http://localhost:8501` 주소로 앱이 실행됩니다.

---

## 📁 프로젝트 구조

```text
.
├── app.py           # 계산기 메인 소스코드
├── requirements.txt # 의존성 라이브러리 목록
└── README.md        # 프로젝트 설명 문서
```