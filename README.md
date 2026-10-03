# My Coding Practice Archive

기본 문법부터 심화 흐름까지, 개발 공부의 발자취를 기록하는 저장소입니다.

- **구성**: 언어별 폴더(C, C++, Java, Python, JavaScript, HTML, CSS, Linux), 각 폴더는 `기초` / `심화` 단계로 나뉨
- **형식**: 주제별 예제 코드(`.c`, `.cpp`, `.java`, `.py`, `.js`, `.html`, `.css`)와 개념 정리 문서(`.md`)
- **GitHub**: [github.com/Seung1won-dot](https://github.com/Seung1won-dot)

<br/>

## 소개

이 저장소는 다양한 프로그래밍 언어의 기초 문법, 핵심 개념, 그리고 알고리즘 예제들을 정리하기 위해 만들어졌습니다. 단순히 코드를 저장하는 것을 넘어, 학습한 내용의 **흐름(Flow)** 을 이해하고 기록하는 것을 목표로 합니다.

## 기술 스택

제가 현재 학습하고 연습 중인 언어들입니다.

<!-- 뱃지 부분: 더 필요한 언어가 있으면 shields.io에서 추가 가능합니다 -->
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) 
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 

## 언어별 학습 내용

각 언어별 폴더는 다음과 같은 내용을 담고 있습니다. 폴더마다 언어 개요를 정리한 문서(`<언어>.md`)가 함께 있습니다.

| 폴더 | 설명 | 주요 학습 내용 | 개요 문서 |
|:---:|:---|:---|:---|
| [C](./C) / [C++](./C++) | 시스템 프로그래밍의 기초 | 포인터, 메모리 관리, 자료구조 기초 | [C.md](./C/C.md), [C++.md](./C++/C++.md) |
| [Java](./Java) | 객체지향 프로그래밍(OOP) | 클래스, 상속, 인터페이스, JVM 구조 | [Java.md](./Java/Java.md) |
| [Python](./Python) | 데이터 처리 및 알고리즘 | 기본 문법, 라이브러리 활용, 코딩 테스트 예제 | [Python.md](./Python/Python.md) |
| [HTML](./HTML) / [CSS](./CSS) | 웹 표준 및 퍼블리싱 | 시맨틱 태그, 레이아웃 구조, 스타일링 연습 | [HTML.md](./HTML/HTML.md), [CSS.md](./CSS/CSS.md) |
| [JavaScript](./JavaScript) | 웹 동적 제어 | ES6+ 문법, DOM 조작, 비동기 처리 | [JavaScript.md](./JavaScript/JavaScript.md) |
| [Linux](./Linux) | 리눅스 명령어와 셸 | 기본 명령어, 파일시스템과 권한, vi, 파이프/grep/sed/awk, 프로세스, 네트워크, 셸 스크립트 | [Linux.md](./Linux/Linux.md) |

## 폴더 구조

각 언어 폴더는 `기초` / `심화` 단계 아래에 주제별 하위 폴더로 구성되어 있습니다.

```
coding-practice-archive/
├── C/
│   ├── C 기초/           기초, 제어문, 함수, 배열과문자열, 포인터기초
│   ├── C 심화/           고급포인터, 메모리관리, 구조체, 파일입출력, 표준라이브러리,
│   │                     전처리기, 알고리즘(정렬), 자료구조(연결 리스트, 스택/큐)
│   └── C.md
├── C++/
│   ├── C++ 기초/         기초문법, 함수, 클래스기초
│   ├── C++ 심화/         상속과다형성, 연산자오버로딩, 템플릿, STL, 예외처리,
│   │                     파일입출력, 메모리관리(스마트 포인터, 복사/이동)
│   └── C++.md
├── Java/
│   ├── Java 기초/        기초, 제어문, 배열과문자열, 클래스와객체, 상속과다형성,
│   │                     예외처리, 컬렉션프레임워크
│   └── Java.md
├── Python/
│   ├── 파이썬 기초/      기초, 제어문, 자료구조, 함수와모듈, 파이썬스러운문법
│   ├── 파이썬 심화/      데이터처리및자동화, 자료구조, 알고리즘-정렬,
│   │                     알고리즘-탐색및고급, GUI프로그래밍및배포
│   └── Python.md
├── JavaScript/
│   ├── JavaScript 기초/  기초, 함수, 객체와배열, DOM
│   ├── JavaScript 심화/  이벤트, 비동기, 고급(클로저, 클래스, 모듈)
│   └── JavaScript.md
├── HTML/
│   ├── HTML 기초/        기초, 기본태그, 리스트와미디어
│   ├── HTML 심화/        폼과시맨틱, 메타와접근성, html5고급
│   └── HTML.md
├── CSS/
│   ├── CSS 기초/         기초, 박스모델
│   ├── CSS 심화/         FlexboxGrid, 반응형, 애니메이션, 고급
│   └── CSS.md
└── Linux/
    ├── Linux 기초/       기초, 파일시스템, 텍스트편집
    ├── Linux 심화/       쉘고급, 프로세스시스템, 사용자관리, 네트워크,
    │                     셸스크립트, 압축과아카이빙
    └── Linux.md
```

파일 이름 앞의 번호(`00_`, `01_` ...)는 학습 순서를 나타냅니다.

## 학습 로드맵

저는 아래와 같은 흐름으로 학습을 진행하고 있습니다.

1.  **Basic Syntax**: 변수, 자료형, 제어문 등 언어의 기초 뼈대 익히기
2.  **Core Concept**: 각 언어만의 핵심 철학 이해하기 (예: Java의 OOP, C의 포인터)
3.  **Algorithm & Logic**: 문제를 해결하는 논리적 사고력 기르기
4.  **Mini Project**: 배운 내용을 종합하여 작은 기능 구현해보기

## Author

꾸준히 성장하는 개발자가 되겠습니다.

- **GitHub**: [github.com/Seung1won-dot](https://github.com/Seung1won-dot)
