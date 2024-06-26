# 질문 잘하는 법

## 0부: 하지 말아야 할 것

* 질문해도 되냐고 묻지 마십시오
  * 그냥 질문을 바로 하라고!!!
* 사람을 찾지 마십시오
  * "~~ 아는 사람 있나요?" 같은 질문을 빙자한 호구 잡기는 제발 좀 하지 마라
  * 손 드는 사람에게 모든 답변의 책임을 떠넘기는 아주 파렴치한 행동이다
  * 그냥 본론으로 들어갔으면 답변해줄 사람도 저렇게 물어보면 답변 절대 안해준다
* 사람을 콕 집어서 답변을 요구하지 마십시오
  * 남에게 책임을 물을 거라면 최소한 돈이라도 내던가

당신의 질문에 대해 답변이 주어지는 것은 당신에게 무슨 자격이 있기 때문이 아니라 순전히 호의에 의한 겁니다. 호의를 베푸는 사람을 공짜 답변 자판기로 보는 사람에게 우리는 호의를 베풀지 않을 겁니다.

## 1부: 백준 질문

### 질문하기 전에

* [질문 게시판 공지사항](https://help.acmicpc.net/question)을 확인하십시오.
  * [자주 하는 답변](https://djm03178.tistory.com/category/PS/%EC%9E%90%EC%A3%BC%20%ED%95%98%EB%8A%94%20%EB%8B%B5%EB%B3%80)도 읽어보면 좋습니다.
* 질문 게시판을 확인하십시오.
  * 많이 풀린 문제라면 높은 확률로 온갖 질문이 널려 있습니다.
  * 높은 확률로 그 중에 당신과 같은 이유로 틀린 사람이 있습니다.
  * 언어를 가리지 말고 답변으로 달린 반례는 전부 돌려보십시오.
  * 질문자의 코드를 읽는데 시간을 낭비하지 마십시오. 그쪽도 글러먹은 코드라서 질문을 올린 겁니다.
  * 답변자의 설명을 읽어보십시오. 이쪽이 타율이 좋습니다.
* 채점 결과를 확인하십시오.
  * 컴파일 에러
    * 백준 해당 문제의 "내 제출" 탭에서 "컴파일 에러"를 클릭하십시오.
    * 컴파일 에러의 경우 에러 메시지를 제공합니다.
    * 에러 메시지를 읽어보고 코드에서 문제가 되는 부분을 고치십시오.
    * 에러 메시지가 무슨 뜻인지 모르겠다면 그대로 복사해서 구글에 검색하십시오.
  * 틀렸습니다
    * 제출한 코드를 **그대로** 실행해보았습니까?
      * 혹시 디버깅을 위해 수정한 것이 있지는 않습니까?
    * 실행 환경이 올바릅니까?
      * `scanf_s` 같은 것을 쓰고 있지 않습니까? 이런 함수는 백준 채점 환경인 gcc 상에서는 사용할 수 없습니다.
      * [tio.run](https://tio.run/#)과 같은 온라인 컴파일러에서 실행해보십시오.
    * 예제는 **그대로** 돌려보셨습니까?
      * 입력할 때 띄어쓰기와 줄바꿈을 구별했습니까?
      * 예제 입력을 한 글자도 틀림 없이 그대로 입력했습니까?
      * 예제 입력 옆에 있는 "복사" 버튼을 잘 활용하십시오.
    * 예제 출력과 공백 한 글자도 빠짐없이 일치합니까?
    * 예제만 돌려보신 건 아닙니까? 다른 입력을 만들어서 넣어보셨습니까?
    * 입력 조건에 맞는 가장 작은 입력과 가장 큰 입력을 만들어서 넣어보셨습니까?
    * 그 밖의 다양한 입력을 넣어보셨습니까?
    * 질문 게시판의 반례는 전부 넣어보셨습니까?
  * 시간 초과
    * 시간복잡도가 무엇인지 아십니까? 모른다면 공부하십시오.
    * 빠른 입출력을 사용하고 계십니까? 모른다면 [이 문제](https://www.acmicpc.net/problem/15552)를 풀어보고, 앞으로 **모든** 문제를 풀 때 적용하십시오.
    * 혹시 Python 3로 제출하고 계십니까? Python 3는 느립니다. [PyPy3로 제출하십시오.](https://djm03178.tistory.com/16)
* 혹시 어떤 입력에서 틀리는지 알아내셨습니까?
  * 그러면 디버깅은 **제발 좀 스스로** 하십시오.
  * 디버거를 쓸 줄 모른다고요? 출력문은 쓸 줄 알 것 아닙니까. 코드 중간에 디버깅용 출력문을 넣어서 각 시점의 변수의 상태를 스스로 확인하십시오.

### 질문하기

* 채점 결과를 **정확히** 알려주십시오.
  * 단순히 "안된다"고 하면 **혼납니다?**
  * "틀렸다"는 표현을 사용하면 채점 결과로 "틀렸습니다"를 받았다는 뜻인지, 아니면 다른 채점 결과를 받았다는 뜻인지 구별하기 어렵습니다.
  * "채점 결과로 ~~를 받았다"는 표현이 명료합니다.
* 제출한 코드를 **그대로** 주십시오.
  * [오답을 받은 코드를 한 글자의 수정도 없이 전체를 그대로 가져오십시오.](https://djm03178.tistory.com/6)
  * 가장 쉬운 방법은 백준의 코드 공유 기능을 이용하는 것입니다.
    * 문제가 된 제출의 언어명을 클릭하면 해당 코드를 확인할 수 있습니다.
    * 그 코드 창의 오른쪽 아래에 "공유" 버튼이 있습니다.
    * 이를 누르면 해당 소스 코드를 로그인 없이 볼 수 있는 링크가 제공됩니다.
    * 이 링크를 그대로 복사해서 공유해주십시오.
  * [ohmy.codes](https://ohmy.codes/), [pastebin.com](https://pastebin.com/)과 같은 코드 공유 사이트를 이용해도 좋습니다.
  * 코드를 복사해서 채팅창에 그대로 붙여넣지 마십시오.
    * 도배나 다름 없습니다.
  * 코드를 캡쳐해서 이미지로 올리지 마십시오.
    * 실행해보고 싶으면 눈으로 보고 코드를 따라서 치라는 말입니까? 양아치세요?
  * 본인이 접근한 방식에 대한 설명과 시도해본 입력을 덧붙이면 좋습니다.
* 코드가 예상치 않게 동작하는 상황입니까?
  * 구체적으로, "이러한 입력을 넣었을 때 코드의 어느 부분에서 이렇게 동작할 것이라고 예상했는데 실제로는 이렇게 동작해서 예상을 벗어났다"고 설명하십시오.
  * [Minimal, reproducible example](https://stackoverflow.com/help/minimal-reproducible-example)을 제공해줄 수 있으면 정말 훌륭합니다.
