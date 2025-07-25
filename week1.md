# 개발자로서 학습과 성장을 위해 AI 사용하기

## ❓AI, 언제 쓰세요?

- 설계나 데이터를 물어보고 개선해나갈 때 사용.

* 체크포인트 기준을 잡을 때 사용한다.

- 코드 검토할때 위주로 사용하고, 설계 방향성에 대해서도 물어볼 때 사용한다.

- 마찬가지지만 검토할 때 주로 사용

* 방향성에 대해 많이 물어본다.

* 내가 학습한 지식에 부족한 점은 없는지 제대로 이해했는지 확인할 때 사용한다.

* 자소서 쓸 때 많이 사용한다.(검색할 때 구글 대신 AI로 검색)

## 🤔AI 활용 고민

- 어느 정도 고민을 해보고 물어봐야할 지 모르겠다. 과연 내가 충분히 고민을 했는지, 더 고민해보면 해결이 가능했는지…

- AI가 제공한 정보가 과연 믿을 수 있는 정보인지 확신할 수 없다.

## 💡브레인 스토밍

### 4컷 만화 생성

- 개인회고 -> 4컷만화 생성 -> 슬랙 공유

- CS 지식 학습 만화 생성

  - 비유나 스토리텔링을 통해 이해하기 쉽도록

**\[조사]**

- **Lore Machine(텍스트 입력 -> AI 텍스트 분석 -> 이미지 생성)**

- **CodeToon (코딩 개념을 이해하기 쉽게 만화로 생성)**

- \***\*![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdBa7sNoRDKKW8jGGPJTSsYppHV7H3MtPX3gwDVUtA47H95c_Ghzi_4smgNi893Q6dGKLrP9Vla9xSQ8Ojm9oc8mrJTqiZ6fFmm6yTKMRiGqZpegNnkWlBLnFnDcbJilt36N9IUzg?key=8Xl0Bwq3RclkB27ZCUUu1A)\*\***

### 멘탈 관리 (J278)

- 하루 한 번 격려 메세지 작성

- 명언 추천

- 현재 자신의 감정을 AI에게 전달해 격려나 조언을 받는다

- `WOEBOT` : AI 정신 건강 챗봇

- `답다` : 사용자의 일기나 감정 기록을 통해 격려와 위로 메시지 전달

### 하루 일정 관리

- 미션의 내용과 일정을 전달해 수행 작업 및 시간 계획 생성

- ex) 14:00 \~ 15:30 가상 메모리 관련 자료 학습

- 비슷한 서비스

  - Akiflow: AI 기능 중 사용자의 작업 완료 패턴, 에너지 레벨, 선호도를 학습해 개인화된 작업 순서와 시간 배치를 추천하는 기능이 있음.

  - Reclaim.ai: 사용자의 생산성 패턴과 업무 습관을 분석함. 특정 유형의 작업을 언제 할 때 가장 효율적인지, 어떤 순서로 작업할 때 생산성이 높아지는지 파악해 최적의 루틴을 제안.

### 내가 사용한 프롬프트 평가

- 프롬프트에 따라 답변이 달라지므로

**[조사]**

[LLM으로 프롬프트 실전 성능 평가하기]\(**[**https://insight.infograb.net/blog/2025/06/11/llm-as-a-judge/**](https://insight.infograb.net/blog/2025/06/11/llm-as-a-judge/))\

- 실험

  **단계**:

  ```
  1. 동일한 코딩 문제에 대해 3가지 다른 프롬프트 작성 

  2. 각각 10번씩 실행해서 결과 수집

  3. 정확도, 코드 품질, 설명 명확도로 점수 매기기

  4. 가장 성능 좋은 프롬프트 패턴 분석

  ```

### 오늘의 노래 추천 리스트

- 자신의 기분에 대해 설명하고 이와 연관된 노래 추천 받기

- Slack에 노래 공유

**[조사]**

- **여러 AI에게 텍스트 입력 후 -> 연관된 노래 추천받는 기능이 많음**

### 자신의 애완동물 지브리 스타일로 그려서 공유하기

- Slack 갤러리 채널에 공유하는 이미지를 AI가 새롭게 작성해보기

- 이미지 생성은 사용량이 제한되어 있어 많은 시도는 제한된다

### 묻고 답하기 채널 확인하기

- 궁금한 내용이 있을 때 묻고 답하기 채널을 모두 살펴보기에는 불편

- 채널에 존재하는 메시지를 복사해서 AI에게 해당 내용의 유무 판단

- 또는 크롤링을 이용해서 확인하기
- **\[조사]**

- 1\. Slack 접근 및 생성 권한 획득

- 2\. #묻고 답하기 채널 크롤링해서 가져오기

- 3\. 궁금한 내용을 키워드 중심으로 찾기

### 여러 생성형 AI 평가

- 어떤 AI가 가장 내 스타일에 맞는가?

- 동일한 질문(프롬프트)을 사용했을 때 어떤 AI가 가장 적절한 결과를 도출하는가?

- 월요일에 수행한 미션의 키워드 map, set, hashtable 개념을 질문하는 프롬프트 만들기

- <https://creatoreconomy.so/p/an-opinionated-guide-on-which-ai-model-2025>

## ❗퀘스트

### Quest 1. “기초 개념 설명력 비교하기”

목표: CS 기초 개념 질문 (Ex. 스택과 힙, 가상 메모리 등)에 대해 각 AI가 어떻게 설명하는지 비교

실행 방법:

- 동일한 질문을 최소 3종의 AI에게 입력

- 설명의 정확성, 예시 제공 여부 등을 기준으로 비교

- 결과를 표로 정리하고, 자신이 가장 만족한 답변과 그 이유를 주관적으로 작성

### Quest 2. “코드 예제 생성 능력 비교하기”

목표: 간단한 코드 구현 요청 (Ex. DFS 탐색, 이진 탐색 등)에 대해 AI가 제시하는 코드 품질 비교

실행 방법:

- 동일한 문제를 각 AI에게 코드로 요청

- 코드의 정확성, 가독성, 예외 처리 등을 기준으로 평가

- 본인이 직접 실행해보고 작동 여부 확인 -> 결과 요약

### Quest 3. “시스템 설계형 질문 대응력 비교하기”

목표: “웹서버의 구조를 설계해줘”와 같은 고차원 질문에 대한 답변 비교

실행 방법:

- AI가 설계 흐름을 얼마나 논리적으로 설명하는지, 그림 없이 말로 이해가 되는지 판단

- 각 AI의 답변을 읽고, 가장 설득력 있었던 부분과 부족했던 점을 주관적으로 메모

### Quest 4. “내 스타일과 맞는 AI는?”

목표: 앞선 퀘스트 결과를 바탕으로, 가장 자신과 잘 맞는 AI를 선정

실행 방법:

- 각 퀘스트별 결과 요약 후, 자신이 생각하는 ‘베스트 AI’를 한 줄로 명시

- “이 AI가 좋은 이유”와 “이 AI가 나와 맞지 않은 이유”를 정리

- 전체 비교표, 주관적 총평, 사용 팁 등을 정리해서 결과 제출

# 퀘스트 수행

## Quest 1. “기초 개념 설명력 비교하기” - `J025`

### 선택 이유

- 평소에 미션 진행할 때 필요한 지식들을 AI한테 많이 물어보는데, 여러 AI를 비교해본 적이 없어 어떤 AI가 좋을지 알 수 있을거 같음
- 여러 AI의 성능과 스타일을 볼 수 있어서 나한테 맞는 AI가 무엇인지 알아낼 수 있을거 같음

### 수행 과정

- 질문을 정해서 각 3개의 AI에 물어봄
- Gemini(2.5 Flash), Claude(Sonnet 4), ChatGPT(GPT-4o)
- 새로운 채팅창으로 진행(사전 질문 X);

##### Day06 - 객체지향 보드게임

- 질문: 객체지향 프로그래밍에 대해 설명해줘
- Gemini: 객체지향 프로그래밍의 정의, 핵심 개념, 장점을 설명해줌, 예시는 현실로 비유해줌
- Claude: 객체지향 프로그래밍의 정의, 핵심 개념, 주요 특징(핵심 개념과 비슷함), 장점을 설명해줌, 예시는 현실로 비유해줌
- ChatGPT: 객체지향 프로그래밍의 정의, 핵심 개념, 목적, 자바스크립트 예시를 보여줌
- 1일차 정리: 내용은 다 비슷하다고 생각하는데, 글로 출력해주는 방식이 달랐다. 클로드는 볼드체나 강조 표시가 안되어있어 중요한 부분이 눈에 안 들어오는 반면 제미나이와 챗지피티는 강조 표시가 잘 되어 있고, 특히 챗지피티는 이모지까지 같이 들어있어 눈에 잘 들어오고 실제 코드 예시가 있어 코드에서 객체지향의 개념이 어떻게 돌아갈까를 생각해볼 수 있어 챗지피티의 답변이 제일 좋았음.

##### Day07 - 가상 파일 시스템

- 질문: FAT12에 대해 설명해줘
- Gemini: FAT12의 개념, 주요 특징과 구조, 특징과 용도, 단점을 설명해줌, FAT12 이후 발전된 FAT16, FAT32에 관한 간단한 설명도 있음
- Claude: FAT12의 개념, 주요 특징, 동작 원리, 한계점을 설명하면서 FAT12 이후 새로운 시스템이 나온 이유를 알려줌
- ChatGPT: FAT12의 개념, 구조, FAT 테이블 예시, 특징 및 한계, 용도를 설명해줌, 다른 질문을 만들어서 이런게 궁금하면 더 설명해 줄 수 있다고 얘기해줌
- 2일차 정리: 내용이 비슷하면서도 조금씩 달랐다. Gemini는 FAT12의 전반적인 지식을 알려주는 느낌으로 각 항목마다 설명이 많아서 이해하기 좋았다. Claude는 중요한 개념만 알려주고 그 개념에 대한 부가 설명이 없어 간결했다. ChatGPT는 개념에 대한 예시도 있고 쉽게 풀어 설명해주는 느낌이 있었다. 파일 시스템에 대한 개념이 없으면 ChatGPT가 제일 좋고, 자세한 개념을 알고 싶으면 Gemini가 좋다고 느꼈다.

##### Day08 - 함수형 프로그래밍

- 질문: 함수형 프로그래밍에 대해 설명해줘
- Gemini: 함수형 프로그래밍의 개념, 핵심 개념(순수 함수, 불변성, 고차 함수, 선언적 프로그래밍)과 예시, 사용하는 이유, 지원하는 언어, 결론, 더 궁금한 점이 있냐고 물어봄
- Claude: 함수형 프로그래밍의 개념, 핵심 개념(순수 함수, 불변성, 고차 함수)와 예시, 주요 특징, 장점, 대표적인 함수형 언어
- ChatGPT: 함수형 프로그래밍의 개념, 핵심 개념(순수 함수, 불변성, 고차 함수, 일급 시민, 선언형 프로그래밍)과 예시, 장점, 자주 쓰이는 함수형 도구(메소드나 라이브러리), 요약
- 3일차 정리: 설명해준 개념은 3개 다 비슷한 느낌으로 설명해주었다. 3번 물어보는 중인데 확실히 Claude는 설명이나 글이 다른 AI보다 훨씬 짧다고 느꼈다. ChatGPT는 간단한 설명과 코드로 된 예시가 많았고 Gemini는 설명 하나하나가 엄청 길었고 예시는 간단한 변수 선언이나 메소드였다. 설명이 길고 양이 많은 점에서 학습하기에 Gemini가 적절하다고 느꼈다.

##### Day09 - 레이스 컨디션

- 질문: 레이스 컨디션에 대해 설명해줘
- Gemini: 레이스 컨디션의 개념, 이름의 유래, 주요 특징 및 문제점, 발생하는 시나리오, 예시, 해결 방법,
- Claude: 레이스 컨디션의 개념, 발생원인, 예시, 해결방법
- ChatGPT: 레이스 컨디션의 개념, 예시, 코드 예시, 해결 방법, 요약
- 3일차 정리: Gemini가 제일 설명이 알차고 많은 것을 설명해주었다. 예시에서는 코드는 없었지만 다른 AI와 다르게 자세하게 풀어 설명해주었고, 다른 AI의 예시는 진짜 간단한 한줄 예시였다. 설명을 보고 이해하기 편한 건 Gemini였다.

##### 총정리

| 질문 (Day)                   | AI 모델 | 설명 내용                                                   | 예시 방식                     | 강조 및 가독성          | 총평 (사용자 의견)                              |
| ---------------------------- | ------- | ----------------------------------------------------------- | ----------------------------- | ----------------------- | ----------------------------------------------- |
| 객체지향 프로그래밍 (Day 06) | Gemini  | 정의, 핵심 개념, 장점                                       | 현실 비유                     | 강조 표시 잘 되어 있음  | 내용 유사하나 가독성 좋음                       |
|                              | Claude  | 정의, 핵심 개념, 주요 특징, 장점                            | 현실 비유                     | 볼드체, 강조 표시 없음  | 중요한 부분 눈에 안 띔                          |
|                              | ChatGPT | 정의, 핵심 개념, 목적, JavaScript 예시                      | 실제 코드 예시                | 강조 표시, 이모지 활용  | 코드 예시와 가독성이 가장 좋음                  |
| FAT12 (Day 07)               | Gemini  | 개념, 주요 특징 및 구조, 용도, 단점, FAT16/32 간단 설명     | 없음                          | 각 항목 설명 많음       | 전반적인 지식 전달, 자세한 이해에 적합          |
|                              | Claude  | 개념, 주요 특징, 동작 원리, 한계점, 발전된 시스템 등장 이유 | 없음                          | 중요한 개념만 설명      | 간결하지만 부가 설명 부족                       |
|                              | ChatGPT | 개념, 구조, FAT 테이블 예시, 특징 및 한계, 용도             | FAT 테이블 예시               | 쉽게 풀어 설명          | 개념 이해가 쉽고 예시가 도움 됨, 심화 질문 유도 |
| 함수형 프로그래밍 (Day 08)   | Gemini  | 개념, 핵심 개념(순수 함수, 불변성, 고차 함수, 선언적 등)    | 간단한 변수 선언/메소드       | 설명 하나하나가 김      | 설명이 길고 양이 많아 학습에 적절               |
|                              | Claude  | 개념, 핵심 개념, 주요 특징, 장점, 대표 언어                 | 예시 포함                     | 설명과 글이 짧음        | 간결하지만 설명이 짧음                          |
|                              | ChatGPT | 개념, 핵심 개념, 예시, 장점, 자주 쓰이는 도구               | 코드 예시 많음                | 간단한 설명과 코드 예시 | 간단한 설명과 코드 예시가 많음                  |
| 레이스 컨디션 (Day 09)       | Gemini  | 개념, 이름 유래, 주요 특징, 시나리오, 예시, 해결 방법       | 자세한 시나리오 설명 (코드 X) | 설명이 가장 알참        | 설명이 알차고 이해하기 편함                     |
|                              | Claude  | 개념, 발생 원인, 예시, 해결 방법                            | 간단한 예시                   | 간결함                  | 핵심 내용 위주                                  |
|                              | ChatGPT | 개념, 예시, 코드 예시, 해결 방법, 요약                      | 코드 예시                     | 코드 예시 제공          | 코드 예시가 있어 이해에 도움                    |

### 수행 결과

## Quest 2. “코드 예제 생성 능력 비교하기” - `J131`

### 선택 이유

- AI가 제시한 코드를 **직접 실행해보고 작동 여부를 확인**할 수 있어서, 결과를 객관적으로 평가하기 좋을 것 같음
- 같은 문제를 주더라도 AI마다 **작성 방식, 함수 분리, 주석 처리, 테스트 코드 유무** 등이 다르기 때문에,
  **AI의 개발자 친화도**를 가늠하기에 적합하다고 느낌

### 수행 결과

#### Day06

- Gpt, Claude, Gemini에게 생성을 요청했다.
- 오늘 미션에 맞춰서 클래스, 객체, 인스턴스 생성 예제, 추상화 예제 등을 실행시켜봤는데, 아무래도 기초 개념에 대한 예제를 생성해달라고 하다보니 각 AI의 예제 생성 능력을 비교하기에는 간단한 예제였다.
- 대부분 아래 예시와 구성은 거의 동일하였고, 어떤 주제인지의 차이만 보였다.
- 다음부터는 함수 분리, 주석 처리, 테스트 코드 유무 등을 판단할 수 있는 예제를 생성해달라고 요청해야겠다.

```js
// 메뉴의 기본 설계도
class MenuItem {
  constructor(name, price) {
    this.name = name; // this = 생성된 객체 자신
    this.price = price;
  }

  getInfo() {
    console.log(`📦 ${this.name}: ${this.price}원`);
  }
}

// 인스턴스 생성 (new → constructor → this에 속성 설정됨)
const americano = new MenuItem("아메리카노", 3000);
const latte = new MenuItem("라떼", 3500);

americano.getInfo(); // 📦 아메리카노: 3000원
latte.getInfo(); // 📦 라떼: 3500원
```

#### Day08 - 클로저 예시 코드 구현 요청

- gpt 4o, claude sonnet 4, gemini 2.5 pro에게 각각 요청
- gpt, gemini는 구현, 설명 순으로 반복해서 답변하고 claude는 구현 완성 후 간단하게 설명을 하는 식으로 답변했다.
- 학습을 위한 예시로는 gpt, gemini가 가독성이 좋다고 느꼈다.
- 예외처리 부분에서는 3가지 ai 모두 완벽하지 않았지만, gpt와 claude는 일부분 예외처리가 있었고 gemini는 예외처리가 아예 없었다.
- claude는 실용 예시가 많았고, gpt는 설명과 구조가 간결했다.
- 이번 코드 구현 예시는 코드만 봤을 때는 claude가 실행시켰을 때 콘솔로그가 잘되어있어서 좋았고, 전체적인 답변은 gpt가 좋았다.

#### Day09 - 비동기 예시 코드 구현 요청

- gpt 4o, claude sonnet 4, gemini 2.5 pro에게 각각 요청
- gpt, gemini는 콜백 기반, Promise 기반, async/await 기반 총 3가지 예시를 구현해줬고, 코드 또한 유사했다.
- claude는 콜백, Promise, async/await 뿐만 아니라 Promise.all, Promise.allSettled, Promise.race, 비동기 이터레이터, 타임아웃, 재시도 로직, 동시 실행 제한 패턴 사용 예시를 구현했다.
- 다양성 측면에서는 claude가 압도적으로 좋았지만, 너무 많은 패턴을 한 번에 구현하다 보니 학습적인 측면에서는 과하다는 생각도 들었다.

## Quest 3. “시스템 설계형 질문 대응력 비교하기” - `J284`

### 선택 이유

- 고차원 질문에 대해 AI가 어떻게 구조적 사고를 전개하는지 확인하고 싶음
- 복잡한 시스템을 말로만 얼마나 설득력 있게 설명하는지 비교해보고, 설득력 있게 설명하는 능력을 배우고 싶음
- 다양한 설계 방식을 접하며 내 시스템 설계 능력도 함께 키우고 싶음

### 수행 결과

## (수행 경험 공유하기) Quest 4. “내 스타일과 맞는 AI는?” - `J025`, `J131`, `J284`

### 선택 이유

- 퀘스트 1, 2, 3을 수행 후 진행 가능한 퀘스트이기 때문에 팀원 모두가 진행 예정

### 수행 결과

#### `J025`

- 개념에 대한 내용은 다 비슷하다고 생각하지만 설명에 대한 자세한 정도, 가독성 등이 Gemini가 나랑 잘 맞는다고 느꼈다.
- Claude는 내가 써봤을 때 설명이 너무 간략하고 다른 AI에 비해 대충 설명하는 느낌이 있어서 별로였다.
- ChatGPT는 가독성도 좋고 설명도 잘 해주지만, 개념의 깊이가 얕다고 느꼈다.
- 퀘스트를 수행할 때 사전 조건 없이 진행했는데 만약 프롬프트로 미리 미션에 대한 정보나 내가 어느정도 지식을 갖고있다는 걸 가정하고 진행했으면 어떨까 싶었다.

#### `J131`

- 기초적인 원리를 학습하기 위해서는 구현과 설명을 작은 단위로 반복하는 gpt가 좋았고, 좀 더 깊게 학습하고 실제 실행을 해보는 측면에서는 콘솔 로그가 자세하게 찍혀있던 claude가 좋았다.

#### `J284`
