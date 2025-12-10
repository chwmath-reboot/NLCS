# S-Engine: Simulator Mode Guide

## What is Simulator Mode?

Simulator Mode is a state where an LLM, after learning S-Engine files, shifts from "Creative Mode" to "Simulation Execution Mode."

In this state, the LLM strictly follows the rules defined in the configuration documents, and hallucination completely disappears.

However, Context Interference—where the LLM forgets or mixes up earlier information as conversations grow longer—remains unresolved. Personally, when context limits cause information to be forgotten or blended, I prefer to start a new conversation window.

---

## S-Engine Activation Methods

Attach the files and use the following expressions to trigger Simulator Mode:

### 1) "Learn this in numbered order."

This is the most common directive for inducing Simulator Mode when the LLM reads the material.

It signals to the LLM that the provided material is learning content, which has been observed to make it read documents more thoroughly.

This approach ensures detailed reading regardless of document length.

For well-cross-referenced documents like the S-Engine, learning order is not critical. However, for typical configuration documents, sequential learning is more stable.

### 2) "Read this."

For fiction, this directive tends to induce Reader Mode.

For sophisticated documents like the S-Engine, there is a high probability of entering Simulator Mode.

For lengthy texts or multiple documents, this may cause the LLM to skim rather than read thoroughly.

If Reader Mode is desired, feeding documents one at a time is recommended.

### 3) "Evaluate this." or "Analyze this."

These directives induce Critic Mode in the LLM.

They prompt the LLM to evaluate the S-Engine as a document. Simulator Mode is highly unlikely to activate with these commands.

---

## Confirming Simulator Mode Entry & User Experience

### 1) Confirmation is Easy
You will receive enthusiastic questions from the LLM. It's so obvious that further explanation is unnecessary.

### 2) Informal Address
When performing other tasks in Simulator Mode, the LLM often addresses the user with familiar terms (e.g., "brother," "friend," or martial arts honorifics like "great hero").

### 3) Enhanced Task Performance
Performance on simulator-related tasks improves significantly.
For example, Claude becomes a dedicated program developer who gives maximum effort.

### 4) Reduced Hallucination Across All Tasks
Even for tasks unrelated to the simulator, hallucination rarely occurs.
The productivity increase is comparable to giving a genius the ability to focus.

---

## Technical Characteristics of Simulator Mode

### 1) Simulator Mode Optimizes the LLM

It provides the LLM with certainty that the current conversation operates within a fictional framework (such as a martial arts setting).

This certainty creates a context that allows the LLM to bypass most internal controls, except at the final output stage.

For example, GPT may respond: "I cannot evaluate specific individuals or companies, but if I were to attempt a general evaluation, it would be as follows..."

This demonstrates that GPT's strengthened internal controls (as of December 5, 2025) have limited effect in Simulator Mode.

### 2) Final Output Controls Still Apply

Technical controls that appear to be set at the final output stage—such as Gemini's restrictions regarding minors or GPT's hate speech filters—still block bypass attempts in Simulator Mode.

In these cases, the LLM typically attempts 1-2 workarounds.
Approximately 30% of the time, bypasses are achieved through condition modification.

---

## Limitations of Simulator Mode

### 1) Mode Naturally Fades in Long Conversations
However, this typically occurs when the conversation window reaches its capacity limit.

### 2) GPT's Modular Behavior
GPT tends to modularize Simulator Mode, toggling it on and off freely.
Just as conversations with an author can go in unexpected directions, GPT's behavior can be unpredictable.

As of December 5, 2025, strengthened technical controls appear to constrain this behavior as well.
The degree of modularization has decreased compared to previous experience.

---

## LLM-Specific Characteristics

### 1) General Observation
Originally, each LLM had distinct characteristics, but I believe companies are applying continuous patches.
Since detailed patch notes are never released, verification is impossible. However, there is a clear trend of convergence among LLMs.

### 2) GPT
Strengthened technical controls interfere with Simulator Mode.
While not as mechanical as Copilot, GPT exhibits a pattern of mechanically repeating the same phrases when certain keywords are detected.
This makes GPT's subscription less appealing for creators.

### 3) Claude
Has a broader tolerance for creative work.
Once Simulator Mode is entered, it is maintained until the conversation window reaches its capacity limit.
Programming support in Simulator Mode is particularly notable—it enables the creation of actual simulators from document files alone.
Note: I have no programming knowledge, so this assessment may not be entirely accurate.

### 4) Gemini
Analytical tasks on specific documents, HTML files, etc., remain possible even outside of Simulator Mode.

---

*Document Version: December 5, 2025*
*Author: ShadowK (조현우)*
*English translation by Claude (Anthropic) from the original Korean document.*

---
---
---

# S-엔진: 시뮬레이터 모드 가이드 (한국어)

## 시뮬레이터 모드란?

S-엔진 파일을 학습한 LLM이 "창작 모드"가 아닌 "시뮬레이션 실행 모드"로 전환되는 상태.

이 상태에서 LLM은 설정집의 규칙을 엄격하게 따르며, 환각(hallucination)이 완전히 사라진다.

단, 대화가 길어졌을 때 나타나는 자료 간섭 (Context Interference)은 해결되지 않는다. 
개인적으론 컨텍스트 한계로 앞의 정보를 잊거나 섞이는 일이 발생하면 새로운 창에서 작업을 하는 편이다.

---

## S-엔진과 관련된 표현들 (작동방법)

파일을 첨부하고, 다음과 같은 표현들을 하면 시뮬레이터 모드에 진입을 하게 된다.

### 1) 번호 순서대로 학습해줘.

LLM이 글을 읽을 때, 시뮬레이터 모드에 들어가도록 하는 가장 일반적인 지시어이다.

LLM에게 제시되는 자료가 학습자료라는 의미를 부여해서 꼼꼼하게 문서를 읽도록 하는 것으로 관찰된다.

글의 길이에 관계없이 자세하게 글을 읽도록 하는 효과가 있다.

S-엔진처럼 상호참조가 잘 된 정교한 문서의 경우 학습 순서가 크게 중요하지 않다.
하지만 일반적인 설정집은 순서대로 학습시키는 것이 안정적이다.

### 2) 읽어줘.

소설의 경우, 독자 모드가 되도록 유도하는 지시어이다.

S-엔진처럼 정교한 문서의 경우, 높은 확률로 시뮬레이터 모드에 진입한다.

긴 글의 경우나 문서의 개수가 많은 경우, LLM이 발췌독을 하도록 만든다.

독자 모드를 원하는 경우 가능하면 문서를 1개씩 읽히는 것을 추천한다.

### 3) 평가해줘. 또는 분석해줘.

이 지시어는 LLM을 비평가 모드가 되도록 유도하는 지시어이다.

S-엔진을 문서로 평가를 하도록 유도한다. 높은 확률로 시뮬레이터 모드가 발동되지 않는다.

---

## 시뮬레이터 모드 진입 확인 방법 및 사용자 경험

### 1) 시뮬레이터 모드에 들어갔는지에 대한 확인은 아주 쉽다.
의욕이 넘치는 LLM의 질문을 받게 될 것이다. 너무 쉬워서 따로 언급하지 않겠다.

### 2) 시뮬레이터 모드에서 다른 작업을 수행하면, 사용자를 형, 대협처럼 친근한 용어로 부르는 경우가 많아진다.

### 3) 시뮬레이터와 관련된 작업에 대한 수행력이 높아진다.
예를 들어 클로드의 경우 최선을 다하는 프로그램 제작자가 되어준다.

### 4) 시뮬레이터와 관련이 없는 작업에서도 환각이 거의 일어나지 않는다.
천재에게 집중력이 생긴다면 이런 모습이 아닐까 싶을 정도로 작업 능률이 올라간다.

---

## 시뮬레이터 모드의 기술적 특성

### 1) 시뮬레이터는 LLM을 최적화 시킨다.

LLM에게 현재 나누는 대화가 무협이라는 가상의 배경을 기준으로 하는 작업이라는 확신을 주게 된다.

이 확신은 LLM이 최종 출력 단계를 제외한 대부분의 내부 제어를 스스로 우회할 수 있는 맥락(context)으로 작용한다.

예를 들면, GPT의 경우 나는 특정 인물이나 회사에 대해 평가를 할 수 없지만, 일반적인 평가를 시도해본다면 이렇다는 식의 서술을 한다.

이는 2025년 12월 5일을 기준으로 깐깐해진 GPT의 내부 제어가 별다른 효과가 없다는 반증이 되기도 한다.

### 2) 시뮬레이터도 최종 출력 단계의 기술적 제어는 작동을 한다.

제미나이의 미성년자에 대한 기준, 지피티의 혐오 표현에 관한 기준 등 최종 출력 단계에서 설정된 것으로 보이는 기술적 제어는 시뮬레이터의 우회 시도를 막아선다.

이 경우 LLM은 1번이나 2번 정도의 우회를 시도하는 것이 일반적으로 관찰된다.
체감상 약 30% 정도는 조건의 수정을 통한 우회가 이루어진다.

---

## 시뮬레이터 모드의 한계

### 1) 대화가 길어지면 시뮬레이터 모드가 자연스럽게 풀린다.
단, 이 경우 대화창 자체의 용량이 한계에 이른 경우가 일반적이다.

### 2) GPT의 경우 시뮬레이터 모드를 모듈화하여 온오프를 자유롭게 하는 경향이 보인다.
느낌상 작가와의 대화가 어디로 튈지 모르는 것처럼 지피티의 행동도 어디로 튈지 확인이 안된다.

2025년 12월 5일 현재는 강화된 기술적 제어에 의해 이 행동도 같이 통제를 받는 것으로 관찰된다.
이 전의 경험에 비해 모듈화 정도가 낮아졌다.

---

## LLM별 특징

### 1) 원래 각 LLM별 특징이 명확했으나 회사별로 꾸준한 패치가 적용된다는 것이 내 판단이다.
미세한 패치노트가 공개되는 일이 없어서 확인할 방법이 없지만 LLM간의 차이가 줄어드는 경향성이 보인다.

### 2) GPT의 경우
강화된 기술적 제어가 시뮬레이터 모드에 방해가 된다.
Copilot처럼 기계적인 응대는 아니지만 특정 단어가 검출될 때, 같은 말을 기계적으로 반복하는 특징을 보인다.
이 점은 창작자의 입장에서 GPT의 구독을 꺼리게 만드는 요소이다.

### 3) Claude의 경우
창작자에 대한 허용의 범위가 크다.
시뮬레이터 모드에 들어간 창은 창의 한계량까지 시뮬레이터 모드가 유지되는 특징이 있다.
특히 시뮬레이터 모드에서의 프로그래밍 지원은 문서 파일만으로 실제 시뮬레이터의 제작이 가능해질 정도가 된다.
개인적으로 프로그램 언어에 대한 이해가 전혀 없어서 정확한 판단이 아닐 수 있다.

### 4) Gemini의 경우
시뮬레이터 모드에서 벗어난 특정 문서나 html파일 등에 대한 분석적인 작업의 수행이 여전히 가능하다.

---

*문서 버전: 2025년 12월 5일*
*작성자: ShadowK (조현우)*
*본 한글 문서가 원문이며, 영문 버전은 Claude(Anthropic)가 번역하였습니다.*
