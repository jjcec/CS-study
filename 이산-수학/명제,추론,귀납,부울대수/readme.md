영상: https://www.youtube.com/playlist?list=PLD8rdlfZeJk7ijUM8ckwLLNyDKRD2aQa2

### [명제와 연산자](이산-수학/이산수학-기초/명제와-연산자.md)

명제의 참과 거짓은 어떻게 판별할 수 있는가?

- 사실 명제 - 관찰, 측정, 실험, 자연과학
- 논리 명제 - 수학, 형식, 논리학

복합명제 : 단순 명제의 조합

단순 명제의 조합으로 만들어지는 명제를 복합 명제라고 한다.

-> 부정, 곱, 합, 조건 명제, 쌍조건 명제



주의

조건 명제의 진위에서 이해하기 힘든 부분은 p가 거짓이고 q가 참일 때 결과는 참이 된다는 것이다.

p : 네가 시험에서 100점을 받는다.

q : 네가 성적 A를 받는다.

에서 "네가 시험에서 100점을 받지 않으면, 성적 A를 받는다." 라는 명제의 결과가 참이 된다는 것이다.

조건 명제에서 주의할 점은 이 명제는 우리의 일상 언어 사용에서의 원인과 결과, 혹은 가정과 결론의 논리로 해석하지 말고 조건 명제의 값을 정의하는 진리표에 의해서 결정되는 것임을 이해해야 한다는 점이다.

조건 명제는 p가 T이고 q가 F일때만 결과가 F가 된다. 나머지는 다 T이다.



EX)

한 섬에 두 개의 부족이 있다고 하자. 그 중 한 부족 사람은 항상 진실만을 말하고, 다른 한 부족 사람은 항상 거짓말만 한다고 한다. 이때 만일 당신이 그 섬에 가서 그 섬에 금이 있는지를 물었을 때 한 사람이 다음과 같이 말했다고 하자.



" 내가 항상 진실만을 말하는 것과 섬에 금이 있다는 사실은 필요충분 조건이다. "



그렇다면 이 섬에 과연 금이 있는 것일까 없는 것일까?

아님 금이 있는지 없는지 판단할 수 없는 것일까?



#### 명제의 구성
명제는 주어와 술어로 구성되어 있다.

명제는 변수를 포함한 함수로서 표현할 수 있다.



#### 한정사
함수 p(x)의 정의역은 한정사를 사용하여 표현할 수 있다. 한정사에는 all, some 두가지 종류가 존재한다.

- 전체 한정(universal quantification) <br>
x가 갖는 모든 값에 대해서 p(x)가 침인 명제를 p(x)의 전체 한정이라고 한다.
- 존재 한정(existential quantification) <br>
x가 갖는 값 중에서 p(x)가 참이 되게 하는 x가 존재하는 명제를 p(x)의 존재 한정이라고 한다.

#### 논리적 기호로 명제를 표현
- 명료하다
- p 접속사 q 으로 표현한 진릿값이 진리표에 의해 명백하게 판단 가능하다

주어진 문장을 논리적 기호로 표현하는 것은 수학이나, 논리 프로그래밍, 인공 지능 등의 분야에서 매우 중요하다.

지금까지 설명한 명제 함수, 한정사는 문장을 논리적 기호로 표현하는데 사용될 수 있다.

### 추론,연역법과 귀납법

#### 추론
> 우리는 이미 "참"으로 알고 있는 명제(들)로부터 새로운 "참"인 명제를 찾아내려고 한다. 이러한 과정을 통해서 새로운 지식을 얻게 된다.
이러한 과정을 추론이라고 한다.
올바른 추론의 규칙을 우리는 논리라고 부른다.
전제에서부터 결론을 얻으려는 과정이 추론. 이러한 추론의 방법으로 두가지가 있다. => 연역법과 귀납법!

#### 연역법
연역법은 형식 논리의 다음과 같은 명제의 틀에 기반을 두고 있다.

if P, then Q (전제)

P (전제)

--------------

Q (결론)



EX) Aristotle의 연역법 예

All men is mortal. 모든 사람은 죽는다. (전제)

Socrates is a man. 소크라테스는 사람이다. (전제)

Therefore, Socrates is mortal. 소크라테스도 죽는다. (결론)

이게 올바른 추론인가?



전제가 모두 T이면 결론도 T가 맞는가.



수학의 이론은 연역법에 의해 만들어진 명제들로 이루어진다.

가정, 정의, 이미 증명된 정리 -> 정리

#### 귀납법

> 개별적인 사실을 말하는 명제들로부터 일반적인 결론을 도출하는 방법
연역법하고 추론의 방향이 다르다고 할 수 있다.
모든 원소에 대해서 T인 것을 보여주면, 이 집합의 모든 원소에 대해서 이 명제는 T라는 것을 보여준다.

EX)

김철수, 이영희, 홍복동은 컴퓨터공학과 학생이다.

김철수는 C언어를 수강한다.

이영희는 C언어를 수강한다.

홍복동은 C언어를 수강한다.

따라서 모든 컴퓨터공학과 학생들은 C언어를 수강한다.



이 경우, 모든 컴퓨터공학과 학생들이 C언어를 수강한다고 할 수 있나?

놉! 김철수, 이영희, 홍복동 세명만 판단해서 전체를 다 그렇다고 판단할 수는 없다.

이것이 바로 귀납법의 한계가 된다.



#### 귀납법의 한계
> 귀납법의 문제는 현실적으로 집합의 모든 원소에 대해서 참인 것을 밝힐 수 없다는 점이다. 따라서 도출된 결론은 기껏해야 확률적인 결론일 수 밖에 없다.


### 수학적 귀납법

> 하지만, 수학적 귀납법은 이러한 귀납법의 한계를 극복
집합의 모든 원소에 대해서 명제가 성립하는 것을 보여준다.
따라서, 모든 경우에 명제가 성립하는 것을 증명할 수 있다.

n = 1일때 P(X1)이 참임을 보인다.

n = k (k>1)일 때 P(X k)이 참임을 가정한다.

n = k+1일때 P(X k+1)이 참임을 보인다.

그렇다면 모든 P(X)에 대해서 참이다.



#### 연습 문제 (연역과 귀납)
다음의 추론은 연역법인가 귀납법인가? 이 추론에 의해 도출된 결론은 참이라 할 수 있는가? 이유는 무엇인가?



1. " 만약 세금을 낮추면 소득이 올라간다. 그런데 소득이 올라갔다. 따라서 세금이 낮아졌다. "



p : 세금을 낮춘다.

q : 소득이 올라간다.

p -> q (전제 T)

q (전제 T)

------------------

p (결론 ?)



보통 추론에서 결론이 p가 아니라 q가 되어야 하는데 이 문제에서는 p가 된다. 따라서 알 수 없다.

추론은 연역법에 의한 추론. 도출된 결론은 참이라고 할 수 없다. 결과는 알 수 없다.

<br>




2. " 대학을 졸업하면 인생이 보장된다. 그런데 나는 대학생이고 곧 졸업할 것이다. 따라서 나의 인생은 보장된다. "



p : 대학을 졸업한다.

q : 인생이 보장된다.



p -> q 사실 명제를 봤을 때 '대학을 졸업하면 인생이 보장된다'는 어떤 근거로 말할 수 있는가. 사실로써 증명하기 힘들다.

연역법을 따르고 있긴 하지만 전제를 참으로 인정할 수 없어서 도출된 결론은 참이라고 할 수 없다.

<br>

3. " 우리 대학을 20년 전에 졸업한 졸업생들의 연소득은 10억이다. (무지하게 많다는 뜻) "



전제 : 우리 대학을 졸업했다.

결론 : 연소득은 10억이다.



이것은 귀납법이다. 우리 대학을 졸업한 학생들을 모두 살펴보았기 때문이다.

이 명제는 참이라고 할 수 있는가? 모순이 있다.

모든 졸업생들이 조사에 참여했다고 할 수 없다. 일부만 응답을 했을 것이다. 그 사람들의 평균 연소득이니 이 사람들이 모든 학생들을 대표할 수는 없기 때문이다.

귀납법에서 흔히 저지르는 과도한 일반화. 부분을 가지고 전체를 이야기하기.



#### 정리
- 결론을 도출하기 위해 사용한 전제가 무엇인가?
- 그 전제는 참인가?
    - 사실로 입증되었나?
    - 가정(전제)인가?
- 전제에서 결론을 도출하는 추론은 합당한가?
- 용어는 확실히 정의되어 있는가?


### [부울 대수(Boolean Algebra)](이산-수학/명제,추론,귀납,부울대수/부울-대수.md)

### 논리회로 설계

> 논리 회로 설계 문제 -> 입력, 출력값 정의 -> 부울 함수 정의 -> 부울식(논리식) -> 부울식 최소화 -> 논리 회로 설계
- 부울 대수
- 부울 함수의 표현
- 부울식의 최소화
- 논리 회로의 설계


#### 부울 대수
공리, 정의. 출발점을 정의한다. 여기서부터 모든 이야기를 전개시켜 나가겠다 일종의 약속



집합 S = {0, 1}에 대해 다음의 세가지 연산이 존재한다.

보수 (complement) : '로 표시 (원소 0에 대하여 0' = 1)
부울 합 (boolean sum) : + (또는 OR)로 표시
부울 곱 (boolean product) : . (또는 AND)로 표시
연산 우선순서 : 보수 >> 곱 >> 합
부울 변수(Boolean variable) : 집합 S = {0, 1}의 원소 값만을 갖는 변수

부울 함수(Boolean function) : 0 또는 1의 입력값들에 대하여 0 또는 1의 출력값을 갖는 함수

부울 식(Boolean expression)의 정의는 재귀이다. 부울 변수 하나하나는 그 자체가 부울식이 된다.

항등(equivalence) : 동일한 변수값에 대해서 진리표의 결과값이 동일하면 두 부울 함수는 동등하다.



EX) 부울 대수의 법칙을 이용하여 다음을 증명하라.

x(x+y) = x



x(x+y) = (x+0)(x+y)  (항등법칙)

         = x + 0y       (분배법칙)

         = x + y0       (교환법칙)

         = x + 0        (지배법칙)

         = x             (항등법칙)



쌍대성의 원리(duality principle)

부울 대수의 모든 항등 법칙에 대하여 다음 2개의 식이 쌍으로 존재한다.

x+0=x, x1 = x

이러한 쌍을 쌍대(dual)라고 한다.

부울식으로 표현된 함수들 사이에 항등성이 유지되면, 이들의 쌍대도 항등성을 유지한다.

부울 대수의 쌍대는 .과 +를 교환하고, 0과 1을 교환하여 구할 수 있다.



논리합 형식(disjunctive normal form) : 곱들의 합

부울 함수를 최소항들의 부울 합으로 나타내는 형식

부울 함수의 부울식은 함수의 값이 1이 되는 변수값의 조합들에 대하여 최소항들을 구하고 그 최소항들의 부울 합(논리합 형식)을 취하면 구할 수 있다.



#### 게이트와 부울 연산
전자 장치의 입력과 출력은 0 또는 1이기 때문에 전자 회로를 설계하는데 부울 대수를 사용할 수 있다.

게이트(gate) : 회로의 기본 요소



기본 게이트와 부울 연산과의 매핑

기본 게이트	부울 연산
인버터 (inverter)	보수
OR 게이트	부울 합
AND 게이트	부울 곱

EX) 부울식과 논리 회로


부울식은 논리 회로로 표현할 수 있다

카르노 맵: 부울식의 최소화
회로를 설계할 때 단순한 식을 사용하는 것이 더 경제적이다. 그러면 더 단순한 부울식이 존재한다면 어떻게 그것을 찾을 수 있을까?


#### 카르노 맵

카노우 맵을 만들 때
1. 변수가 2개면 2x1, 변수가 3개면 4x2, 변수가 4개면 4x4, ...
2. 인접하는 칸들은 동일한 변수를 갖고 있어야 한다.
앞의 예에서 (xy, xy', x'y', x'y)같이 된다.
그리고 인접되는 칸들은 원통처럼 연결되어 있다.
3. 인접하는 칸들을 묶을 때는 2^n, 2^(n-1), ... 순으로 묶는다.
예를 들면 변수가 3개일 때 2^2, 2^1 순서로 인접하는 항을 묶는다.