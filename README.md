# Algorithm-Study

-   기간 : 8월 중반 ~

-   회의 : 매주 목요일 8시 ~ 9시 30분

-   교재 : 코딩 테스트 합격자 되기 - 자바스크립트 편

-   언어 : 자바스크립트

-   😥 프로젝트 기간에는 잠정적 중단

-   노션 : https://www.notion.so/7-09e10c7a9f0542ed840cffaf38dbd17e?pvs=4

<br />

## 스터디 멤버

|                                                  고종원                                                  |                                                  육은별                                                  |                                                  이가은                                                  |                                                  박아영                                                  |
| :------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/user-attachments/assets/e77dbad6-0034-4758-8d50-88460feb9617" width="300"/> | <img src="https://github.com/user-attachments/assets/eea9a733-10de-439a-b012-06799cccc54a" width="300"/> | <img src="https://github.com/user-attachments/assets/c9692fef-9ece-448b-9612-8957f1488c46" width="300"/> | <img src="https://github.com/user-attachments/assets/540e3cd5-6ed4-4505-b605-312cf0de4231" width="300"/> |

<br />

## 스터디 규칙

> **주마다 `4문제` 선정해서 문제 풀이를 진행한다.**

-   **회의시간에는 자신이 담당한 하나의 문제만 설명한다.**

-   [숫자]week-[이름]으로 branch 만들어서 문제.md 작성 후 main branch로 PR하고 코드리뷰를 한다.

-   서로에 대한 코드 리뷰는 토요일까지 완료한다.

-   반드시 코드 리뷰 후에 main branch로 merge한다.

-   코드 리뷰 받은 것에 대해서는 다음 회의 전까지 수정해서 다시 깃허브에 올린다.

### **GitHub 규칙**

```
- 폴더 구조
이름/1주차/[문제 번호] 문제이름.md

- Commit Message
📝 [문제 02] 배열 제어하기

- PR title(한문제만)
[문제 02] 배열 제어하기-육은별

- PR title(네문제)
[숫자]week-[이름]
```

### 이름/1주차/[문제 번호] 문제이름.md 구조

```
# [코딩 테스트 문제 제목]

**[문제 링크]**

## 문제 설명

> [더미 텍스트 더미 텍스트 더미 텍스트 더미 텍스트 더미 텍스트 더미 텍스트]

## 제약 조건

- 배열의 길이는 2이상 1000 이하입니다.
- 각 배열의 데이터 값은 -100000이상 100000 이하입니다.

## 예제 입/출력

### 예제1

**입력**

``
[5, 4, 3, 1, 2]
``

**출력**

``
[1, 2, 3, 4, 5]
``

## 접근 방식

### 시간 복잡도

- **[최대 시간 복잡도]**
- [이유]

### 자료구조

- **[사용한 자료구조]**
- [이유]

### 알고리즘

- **[사용한 알고리즘]**
- [이유]

## 소스 코드

``
javascript
function solution() {
var answer = -1;

console.log('Hello World!');

return answer;
}
``
```

### 코드 리뷰 규칙

> 1사람당 1사람만 담당해서 코드 리뷰를 한다.

> 주마다 돌아가면서 다른 사람을 맡는다.

> 파일마다 템플릿에 맞춰 작성해주면 된다.

-   평가 지표에서 👎인 경우만 이유를 작성한다.
-   👍인 경우는 작성란을 삭제한다.
-   평가 지표에서 👍인 개수를 세어서 맨 위의 점수에 ⭐의 개수로 반영한다.

<br />

```
## ⭐⭐⭐⭐⭐

### reviewer: [이름]

1. 문제가 해결 되었는가? 👍/👎
2. 코드 컨벤션이 잘 지켜졌는가? 👍/👎

    - [👎라면 이유]

3. 논리적인 오류가 없는가? 👍/👎

    - [👎라면 이유]

4. 이전 PR에서 지적된 실수를 반복하진 않는가? 👍/👎

    - [👎라면 이유]

5. 코드의 시간 복잡도를 낮출 수 있는가? 👍/👎

    - [👎라면 방법]

**기타 의견 P[4 ~ 5]**

    - P4: 반영해도 좋고 넘어가도 좋습니다 (Approve)
    작성자는 P4에 대해서는 아무런 의견을 달지 않고 무시해도 괜찮습니다.
    해당 의견을 반영하는 게 좋을지 고민해 보는 정도면 충분합니다.

    - P5: 그냥 사소한 의견입니다 (Approve)
    작성자는 P5에 대해 아무런 의견을 달지 않고 무시해도 괜찮습니다.

    ex) if문 대신에 삼항 연산자를 사용하면 더 간단하게 표현할 수 있어요!
```

<br />

## **설명은 이렇게**

-   적용 알고리즘 개념 간단하게 설명하기

-   문제 풀이를 위한 접근 방식(or 개념) 설명

-   기본 코드에 대한 설명

-   추가적으로 개선한 코드에 대한 설명(없으면 패스)

-   시간 복잡도 계산

-   기타(문제 풀이에 어려웠던 점, 구현하고자 했는데 실패한 방식)
