# My Coding Practice Archive

기본 문법부터 심화 주제까지, 여러 언어를 공부하며 만든 예제 코드와 개념 정리를 모아 둔 학습 기록 저장소입니다.

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Linux](https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

| 항목 | 내용 |
|------|------|
| 학습 목표 | 언어마다 기초 문법 → 핵심 개념(포인터, OOP, 비동기 등) → 알고리즘·응용 순서로 흐름을 직접 코드로 익히기 |
| 학습 범위 | 8개 분야 — C, C++, Java, Python, JavaScript, HTML, CSS, Linux |
| 기간 | 2025-12 ~ 2026-01 (커밋 기준) |
| 형태 | 개인 학습 |
| 형식 | 주제별 예제 코드(`.c` `.cpp` `.java` `.py` `.js` `.html` `.css`)와 개념 정리 문서(`.md`) |
| 상태 | 기초·심화 정리 완료 (Java는 기초까지) |

## 언어별 학습 내용

각 언어 폴더에는 언어 개요를 정리한 문서(`<언어>.md`)가 함께 있습니다.

| 폴더 | 초점 | 주요 학습 내용 | 개요 문서 |
|:---:|:---|:---|:---|
| [C](./C) | 시스템 프로그래밍 기초 | 포인터, 메모리 관리, 구조체, 파일 입출력, 연결 리스트·스택/큐 | [C.md](./C/C.md) |
| [C++](./C++) | 객체지향과 일반화 | 클래스, 상속·다형성, 연산자 오버로딩, 템플릿, STL, 스마트 포인터 | [C++.md](./C++/C++.md) |
| [Java](./Java) | 객체지향 프로그래밍 | 클래스와 객체, 상속·다형성, 예외 처리, 컬렉션 프레임워크 | [Java.md](./Java/Java.md) |
| [Python](./Python) | 데이터 처리와 알고리즘 | 기본 문법, 자료구조, 정렬·탐색·DP, 자동화(크롤링·엑셀·메일), GUI(tkinter·PyQt) | [Python.md](./Python/Python.md) |
| [JavaScript](./JavaScript) | 웹 동적 제어 | ES6+ 문법, DOM 조작, 이벤트, Promise·async, 클로저·클래스·모듈 | [JavaScript.md](./JavaScript/JavaScript.md) |
| [HTML](./HTML) | 웹 표준 마크업 | 기본 태그, 리스트·미디어, 폼과 시맨틱 태그, 메타·접근성 | [HTML.md](./HTML/HTML.md) |
| [CSS](./CSS) | 스타일링과 레이아웃 | 박스 모델, Flexbox·Grid, 반응형, 애니메이션 | [CSS.md](./CSS/CSS.md) |
| [Linux](./Linux) | 리눅스 명령어와 셸 | 파일 시스템과 권한, vi, 파이프·grep·sed·awk, 프로세스, 네트워크, 셸 스크립트 | [Linux.md](./Linux/Linux.md) |

## 예제 실행하기

언어별 기본 도구로 파일 하나씩 바로 실행할 수 있습니다. 파일 이름 앞의 번호(`00_`, `01_` ...)가 학습 순서입니다.

```bash
# C / C++
gcc 파일명.c -o app && ./app
g++ 파일명.cpp -o app && ./app
```

```bash
# Java (JDK 11 이상은 소스 파일을 바로 실행 가능)
java 파일명.java
```

```bash
# Python / JavaScript(Node.js)
python3 파일명.py
node 파일명.js
```

HTML·CSS 예제는 `.html` 파일을 브라우저로 열면 됩니다.

## 프로젝트 구조

각 언어 폴더는 `기초` / `심화` 단계 아래에 주제별 하위 폴더로 나뉩니다.

```text
coding-practice-archive/
├── C/
│   ├── C 기초/           기초, 제어문, 함수, 배열과문자열, 포인터기초
│   └── C 심화/           고급포인터, 메모리관리, 구조체, 파일입출력, 표준라이브러리,
│                         전처리기, 알고리즘, 자료구조
├── C++/
│   ├── C++ 기초/         기초문법, 함수, 클래스기초
│   └── C++ 심화/         상속과다형성, 연산자오버로딩, 템플릿, STL, 예외처리,
│                         파일입출력, 메모리관리
├── Java/
│   └── Java 기초/        기초, 제어문, 배열과문자열, 클래스와객체, 상속과다형성,
│                         예외처리, 컬렉션프레임워크
├── Python/
│   ├── 파이썬 기초/      기초, 제어문, 자료구조, 함수와모듈, 파이썬스러운문법
│   └── 파이썬 심화/      데이터처리및자동화, 자료구조, 알고리즘-정렬,
│                         알고리즘-탐색및고급, GUI프로그래밍및배포
├── JavaScript/
│   ├── JavaScript 기초/  기초, 함수, 객체와배열, DOM
│   └── JavaScript 심화/  이벤트, 비동기, 고급
├── HTML/
│   ├── HTML 기초/        기초, 기본태그, 리스트와미디어
│   └── HTML 심화/        폼과시맨틱, 메타와접근성, html5고급
├── CSS/
│   ├── CSS 기초/         기초, 박스모델
│   └── CSS 심화/         FlexboxGrid, 반응형, 애니메이션, 고급
└── Linux/
    ├── Linux 기초/       기초, 파일시스템, 텍스트편집
    └── Linux 심화/       쉘고급, 프로세스시스템, 사용자관리, 네트워크,
                          셸스크립트, 압축과아카이빙
```

## 학습 흐름

1. **기초 문법** — 변수, 자료형, 제어문 등 언어의 뼈대 익히기
2. **핵심 개념** — 언어마다의 핵심 이해하기 (예: C의 포인터, Java의 OOP, JavaScript의 비동기)
3. **알고리즘과 응용** — 자료구조·정렬·탐색으로 문제 해결력 기르기
4. **작은 프로젝트** — 배운 내용을 묶어 작은 기능 만들어 보기 (예: PyQt로 만든 할 일 목록 앱)

## 더 읽을거리

- 언어별 개요: [C](./C/C.md) · [C++](./C++/C++.md) · [Java](./Java/Java.md) · [Python](./Python/Python.md) · [JavaScript](./JavaScript/JavaScript.md) · [HTML](./HTML/HTML.md) · [CSS](./CSS/CSS.md) · [Linux](./Linux/Linux.md)
- GitHub: [github.com/Seung1won-dot](https://github.com/Seung1won-dot)
