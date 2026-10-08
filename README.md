# 10주차 · JavaScript 기초 문법 이해

변수, 자료형, 조건문, 반복문 등

- 과목: 한신대학교 웹프로그래밍 (AS006-E)
- 주차 강의안: https://hs-web.dreamitbiz.com/weeks/10

## 여는 방법

1. 압축을 풉니다.
2. VS Code 에서 **폴더째로** 엽니다 (파일 → 폴더 열기).
3. `.html` 파일을 더블클릭하면 브라우저에서 바로 열립니다.
   VS Code 라면 Live Server 확장을 쓰는 편이 편합니다 — 저장하면 화면이 바로 바뀝니다.
4. 고쳐 보고, 저장하고, 브라우저를 새로고침(F5)하세요.

**고쳐 보라고 드리는 파일입니다.** 망가뜨려도 괜찮습니다 — 다시 받으면 됩니다.

## 학습 목표

- const와 let을 구분해 쓰고 var를 쓰지 않는 이유를 설명할 수 있다.
- JavaScript의 기본 자료형을 구분하고 형변환의 함정을 피할 수 있다.
- === 와 == 의 차이를 설명하고 항상 === 를 쓸 수 있다.
- 조건문과 반복문으로 흐름을 제어할 수 있다.
- console.log와 개발자도구로 값을 확인하며 문제를 좁혀 갈 수 있다.

## 이번 주 낱말

const/let · 자료형 · 템플릿 문자열 · 형변환 · === · if/else · for · while · console.log · 디버깅

## 담긴 파일

### examples/ — 강의안에 나온 예제 18개

- `examples/01.html` — CSS와 마찬가지로 세 가지
- `examples/02.html` — const와 let
- `examples/03.html` — 규칙과 관례
- `examples/04.html` — 기본형 다섯 + 참조형 둘
- `examples/05.html` — 따옴표 세 종류
- `examples/06.html` — 자주 쓰는 문자열 메서드
- `examples/07.html` — ⚠ 여기서 초보자가 가장 많이 당합니다
- `examples/08.html` — 숫자 다루기
- `examples/09.html` — == 를 쓰지 않는 이유
- `examples/10.html` — && || ! 와 참·거짓 판정
- `examples/11.html` — 실무에서 자주 쓰는 두 가지
- `examples/12.html` — 짧은 분기
- `examples/13.html` — if / else if / else
- `examples/14.html` — switch — 값이 딱 떨어질 때
- `examples/15.html` — for — 횟수를 아는 반복
- `examples/16.html` — for...of — 배열을 훑을 때 (가장 많이 씁니다)
- `examples/17.html` — while — 조건이 참인 동안
- `examples/18.html` — 값을 확인하는 여러 방법

### lab/ — 실습 4개

- `lab/lab1.html` — 실습 1 · 기본
- `lab/lab2.html` — 실습 2 · 기본
- `lab/lab3.html` — 실습 3 · 응용
- `lab/lab4.html` — 실습 4 · 심화

문제와 힌트는 각 실습 파일 맨 위 주석에 그대로 적어 두었습니다.
모범답안은 `lab/answer/` 에 있습니다. **먼저 스스로 해 본 뒤에** 열어 보세요.

## 다 만들었으면

실습 결과를 패들릿에 올려 자랑해 주세요.
주차 강의안 페이지 **맨 위**의 [10주차 실습 자랑하기] 단추로 들어갑니다.

> ⚠ 패들릿은 **서로 보고 배우는 자랑·질문용**입니다. 성적과는 관계가 없습니다.
> 성적에 들어가는 **실습 과제는 학교 LMS에 제출**합니다 — https://lms.hs.ac.kr/

- 실습 결과(화면 캡처) → 「10주차 실습 제출」 칸
- 막히거나 안 되는 것 → 「10주차 질문·막힌 곳」 칸

https://padlet.com/dreamitbiz/hs2605
