## React Example in class(2020-01-02 ~ )

예제를 이용한 함수형 컴포넌트와 클래스형 컴포넌트의 이해, Hook의 사용법

### 1.(0102)Hello- Set : 함수형 컴포넌트, 클래스형 컴포넌트

### 2.(0102)day1 folder : 함수형 컴포넌트, 클래스형 컴포넌트 복습, Hook의 이해 

### 3.(0103)Quiz folder : Hook을 이용한 퀴즈 application 

  

  

  
  
  
------------------------------------------------------------------------------------------------
 
   
   
    
   
   
 
## CLASS NOTE 

### What is React? 
: HTML(JSX) + 상태(option) + 행위(events)의 묶음. <br>
: 독립적인 라이프 사이클을 가지고 있음.(복잡했던 라이프사이클은 Hooks의 도입으로 단순화됐다) <br>
: 등장배경 - 예전엔 MVC(html(순수한데이터(Model)),CSS(View),JS(Controller)-무간섭js)가 유행. <br>
  but... 한꺼번에 만들어서 재사용 하면 좋을텐데? -> html과 js를 분리해놨더니 재사용이 더 힘들어짐 
  -> 이러면서 다시 재등장한 개념이 '컴포넌트' -> html + js로직을 한 단위로 묶어서 재사용이 가능
  -> 컴포넌트(그 하나로써 온전한 기능을 가진 단위) -> 결국 React의 개발방식은 이 컴포넌트를 어떻게 만들어서 잘 쓰느냐가 관건.
: 현실적인 문제들 
  - 기존과 달리 React 컴포넌트는 css까지 컴포넌트의 요소로 활용한다는 점
  - 컴포넌트에 디자인을 입히는 방법에 대한 고민 > 기존 템플릿에 디자인을 입히는 방식 / React에 맞는 템플릿을 사용하는 방식 

### Component 
: 앱을 만들때 빌딩 블럭(컴포넌트)을 만든다고 함.
: 일반 엘리먼트와의 차이점은 (유형에 따라)상태와 독립적인 라이프사이클을 가지고 있다는 점. 

1. 함수형 컴포넌트 <br>
- 함수를 정의한다.  
- 파라미터를 받거나 구조 분해 할당 처리  
- 함수 내에서 필요한 변수나 연산 처리  
- return 값은 JSX처리(JSX의 속성으로는 표현식(expression) 

2. 클래스형 컴포넌트 <br>
- 상태를 유지하고, 여러 하위 컴포넌트들을 컨트롤 할 수 있다.  
- 컴포넌트들을 조합해서 하나의 단위 기능을 만들 경우에 유용하게 사용할 수 있음.
- 그러나 Hooks의 도입이후 최신형 컴포넌트들은 함수형컴포넌트에 hook을 도입하여 사용한다.

### Hook
: React version 16.8에 새로 도입됨 <br>
: class를 작성할 필요 없이 함수형 컴포넌트가 상태(state)를 유지할 수 있음.(useState이용)
- useState : 함수형 컴포넌트가 상태를 유지하는 방법
  : 전통적인 함수는 상태를 유지할 수 없는 방식 > 따라서 클래스형 컴포넌트가 사용되고 있었음. useState가 나온 이후로는 상태 유지 가능.
  





